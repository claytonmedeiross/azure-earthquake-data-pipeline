# Azure Earthquake Data Pipeline

Projeto de Engenharia de Dados desenvolvido utilizando Azure Databricks, PySpark e Azure Blob Storage para ingestão, transformação e armazenamento de dados sísmicos obtidos através da API pública da USGS (United States Geological Survey).

---

# Arquitetura do Projeto

```text
USGS Earthquake API
        ↓
Python Requests
        ↓
Databricks Notebook
        ↓
PySpark DataFrame
        ↓
Delta Table
        ↓
Parquet Files
        ↓
Azure Blob Storage

<img width="1732" height="932" alt="image" src="https://github.com/user-attachments/assets/14e833ae-d2a1-4bcb-8701-91d811a2544b" />
<img width="1032" height="967" alt="image" src="https://github.com/user-attachments/assets/f66d1ef8-9b29-491b-9d02-baac34a6d200" />
