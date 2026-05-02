# Case NPS Preditivo

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

## Sobre o Projeto

O foco principal é analisar dados de NPS (Net Promoter Score) e variáveis relacionadas à experiência do cliente dentro de um e-commerce, com o objetivo de identificar padrões, gerar insights e apoiar decisões estratégicas.

## Objetivo

-Analisar o comportamento dos clientes com base no NPS
-Identificar fatores que impactam a satisfação
-Explorar correlações entre variáveis operacionais e experiência
-Gerar insights acionáveis para melhoria de processos

## Tecnologias / Bibliotecas Utilizadas
Pandas – manipulação de dados
NumPy – operações numéricas
Seaborn / Matplotlib – visualização de dados
Jupyter Notebook – análise exploratória
Scikit-learn

## Estrutura do Projeto

1IAST-Fase1
 ┣  Data_Science_Desafios.ipynb   # Notebook principal do desafio
 ┣  environment.yml              # Ambiente do projeto
 ┣  pyproject.toml               # Configuração do projeto
 ┣  setup.cfg                    # Configuração adicional
 ┣  Makefile                     # Automação de tarefas
 ┣  notebooks/
   ┣  EDA.ipynb                  # Análise exploratória de dados
   ┣  tech_challenge_nps.ipynb   # Análise focada em NPS
   ┗  dict_dados.bin             # Dicionário de dados
 ┣  nps_analysis/                # Módulos Python do projeto
 ┣  models/                      # Modelos treinados
 ┣  reports/
 ┃ ┗ figures/                   # Visualizações geradas
 ┣  tests/                       # Testes automatizados
 ┣  docs/                        # Documentação adicional
 ┗  references/                  # Materiais de apoio

--------

## Como Executar o Projeto

### Clonar o repositório
git clone https://github.com/ldamaske/1IAST-Fase1
cd 1IAST-Fase1

### Criar o ambiente
conda env create -f environment.yml
conda activate 1IAST-Fase1

### Executar os notebooks
jupyter notebook
