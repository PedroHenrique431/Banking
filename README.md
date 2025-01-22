# Análise de Risco em Operações Bancárias

## Descrição

Este projeto tem como objetivo avaliar transações bancárias para identificar padrões de risco e possíveis fraudes. A análise se concentra em detectar transações suspeitas, como aquelas com valores muito altos ou realizadas em horários incomuns, além de criar clusters de perfis de clientes com base em suas operações financeiras. As transações analisadas são geradas de forma simulada para preservar a privacidade dos dados.

## Objetivos

1. **Simulação de Dados**: Gerar transações bancárias fictícias com o uso da biblioteca **Faker**, garantindo a privacidade e anonimato dos dados.
2. **Identificação de Outliers**: Detectar transações com características anômalas, como valores excessivos ou horários atípicos, que podem ser indicativos de fraudes ou risco.
3. **Criação de Clusters de Perfis de Clientes**: Utilizar algoritmos de clustering, como o **KMeans**, para agrupar os clientes em perfis, como clientes transacionais e clientes de investimentos.
4. **Análise e Visualização**: Criar gráficos e análises para ilustrar os padrões encontrados nas transações e nos clusters de clientes.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para simulação dos dados e análise.
- **Faker**: Biblioteca para gerar dados fictícios de transações bancárias.
- **Pandas**: Para manipulação e análise de dados.
- **Scikit-learn**: Para algoritmos de clustering e identificação de outliers.
- **Matplotlib / Seaborn**: Para visualização de dados e gráficos.

## Este repositório contém os seguintes arquivos:

README.md: Explicação sobre o projeto, objetivos, e como executar o código.
main.ipynm: Jupyter Notebook com a análise interativa e visualizações.

## Como Executar o Projeto

### Instalação de dependências

Certifique-se de que as bibliotecas necessárias estão instaladas. Execute o comando abaixo para instalar as dependências:

```bash
pip install pandas scikit-learn matplotlib seaborn faker
