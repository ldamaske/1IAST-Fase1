# Case NPS Preditivo

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

## Sobre o Projeto

O foco principal é analisar dados de NPS (Net Promoter Score) e variáveis relacionadas à experiência do cliente dentro de um e-commerce, com o objetivo de identificar padrões, gerar insights e apoiar decisões estratégicas.

## Objetivo

-Analisar o comportamento dos clientes com base no NPS<br>
-Identificar fatores que impactam a satisfação<br>
-Explorar correlações entre variáveis operacionais e experiência<br>
-Gerar insights acionáveis para melhoria de processos

## Tecnologias / Bibliotecas Utilizadas
Pandas – manipulação de dados<br>
NumPy – operações numéricas<br>
Seaborn / Matplotlib – visualização de dados<br>
Jupyter Notebook – análise exploratória<br>
Scikit-learn

## Estrutura do Projeto
```
1IAST-Fase1<br>
 ┣  Data_Science_Desafios.ipynb               # Notebook principal do desafio
 ┣  environment.yml                           # Ambiente do projeto
 ┣  pyproject.toml                            # Configuração do projeto
 ┣  setup.cfg                                 # Configuração adicional
 ┣  Makefile                                  # Automação de tarefas
 ┣  notebooks/
 ┃ ┣  EDA.ipynb                               # Análise exploratória de dados
 ┃ ┣  tech_challenge_nps.ipynb                # Análise focada em NPS
 ┃ ┗  dict_dados.bin                          # Dicionário de dados
 ┣  nps_analysis/                             # Módulos Python do projeto
 ┣  models/                                   # Modelos treinados
 ┣  reports/<br>
 ┃ ┗ figures/                   # Visualizações geradas<br>
 ┣  tests/                       # Testes automatizados<br>
 ┣  docs/                        # Documentação adicional<br>
 ┗  references/                  # Materiais de apoio<br>
```

--------

## Como Executar o Projeto

### Clonar repositório
```
git clone https://github.com/ldamaske/1IAST-Fase1
cd 1IAST-Fase1
```

### Criar o ambiente
```
conda env create -f environment.yml
conda activate 1IAST-Fase1
```

### Executar os notebooks
```
cd notebooks
jupyter notebook
```
