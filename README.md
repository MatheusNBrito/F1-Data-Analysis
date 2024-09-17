# F1 Data Analysis

Este projeto visa analisar dados da Fórmula 1 para extrair insights valiosos sobre o desempenho dos pilotos e das equipes. Utilizando uma combinação de **Azure Databricks**, **PySpark**, **Azure Data Factory**, e **Power BI**, este projeto demonstra o processamento de grandes volumes de dados e a criação de dashboards interativos para visualização.

## 📚 Sobre o Projeto

O projeto inclui:

- **Coleta e Processamento de Dados**: Utilização de **Azure Data Factory** para automação de ETL, e **PySpark** no **Azure Databricks** para processamento de dados.
- **Armazenamento**: Dados armazenados em **Azure Data Lake** no formato CSV, JSON, Parquet e Delta.
- **Análise de Dados**: Scripts Python e notebooks do **Azure Databricks** para limpeza, transformação e análise de dados.
- **Visualização**: Criação de dashboards interativos com **Power BI** conectados aos dados processados.
- **Gerenciamento de Dados**: Uso do **Unity Catalog** para governança e controle de acesso aos dados.

## 🛠 Tecnologias Utilizadas

- **Azure Databricks**: Para processamento de dados e execução de notebooks.
- **PySpark**: Para transformação e manipulação de dados.
- **Azure Data Factory**: Para automação de pipelines ETL.
- **Azure Data Lake**: Para armazenamento de dados em grande escala.
- **Power BI**: Para criação de dashboards e visualização interativa.
- **Unity Catalog**: Para gerenciamento de dados e governança.

## 🚀 Como Executar o Projeto

1. **Clone o Repositório**:

    ```bash
    git clone https://github.com/seu_usuario/F1-Data-Analysis.git
    cd F1-Data-Analysis
    ```

2. **Data Processing**:

    Execute os scripts de processamento e transformação de dados (`etl_pipeline.py`) no **Azure Databricks**.

3. **Notebooks**:

    Importe os notebooks do **Azure Databricks** (`data_analysis.ipynb`) para explorar a análise de dados.


## 🔍 Exemplos de Análise

Os notebooks e scripts fornecem exemplos de análises realizadas, como:

- Análise do desempenho dos pilotos em diferentes corridas.
- Comparação entre equipes e análise de resultados de corridas.
- Visualizações de métricas-chave como tempos de volta e posições de chegada.




