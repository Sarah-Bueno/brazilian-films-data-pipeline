# 🎬 Brazilian Films Data Pipeline

Pipeline ETL desenvolvido com Python e Pandas para limpeza, transformação e preparação de dados sobre produções cinematográficas.

## 🎯 Objetivo

Transformar uma base bruta de filmes em um conjunto de dados estruturado e preparado para análise, aplicando conceitos de ETL, qualidade e transformação de dados.

## ⚙️ Pipeline ETL

### 📥 Extract
- Leitura da base original em formato ODS
- Carregamento dos dados com Pandas
- Inspeção inicial da estrutura da base

### 🔄 Transform
- Seleção das variáveis relevantes
- Identificação e tratamento de valores ausentes
- Verificação de registros duplicados
- Conversão e padronização dos tipos de dados
- Tratamento de datas
- Criação de novas variáveis
- Validação da qualidade dos dados

### 📤 Load
- Geração de uma nova base tratada
- Exportação dos dados para CSV
- Preparação dos dados para análises posteriores

## 🛠️ Tecnologias

- Python
- Pandas
- Google Colab
- ETL
- Data Cleaning
- Data Transformation
- Data Quality

## 📊 Possibilidades de análise

A base tratada permite explorar questões como:

- Evolução da produção cinematográfica ao longo dos anos
- Distribuição dos filmes por duração
- Diretores com maior número de produções
- Participação em festivais
- Registro de premiações
- Principais produtoras presentes na base

## 📁 Estrutura do projeto

```text
brazilian-films-data-pipeline/
│
├── README.md
├── Brazilian_Films_Data_Pipeline.ipynb
├── data/
│   └── filmes_tratados.csv
└── .gitignore
