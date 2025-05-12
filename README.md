# Azure Data Engineering Pipeline 🌐

This project demonstrates an end-to-end data engineering pipeline using Azure services including Data Lake Storage Gen2, Azure Databricks, Azure Synapse Analytics, and Power BI.

## 🔧 Tech Stack
- **Azure Data Lake Storage (Gen2)** – Bronze, Silver, and Gold layers
- **Azure Databricks** – PySpark for data transformation
- **Azure Synapse Analytics** – External tables and SQL views
- **Power BI** – Data visualization
- **Azure Blob Parameters** – For configuration metadata

---

## 📁 Project Structure

```bash
azure-data-engineering-pipeline/
│
├── data/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── databricks/
│   └── silver_layer_notebook.py
│
├── synapse/
│   ├── create_file_format.sql
│   └── create_external_tables.sql
│
├── powerbi/
│   └── pbix_screenshots/
│
├── parameters/
│   └── git.json
│
└── README.md
