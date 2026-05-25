# 🚀 NYC Payroll Data Engineering Project

## 📌 Overview

This project demonstrates the design and implementation of an end-to-end data engineering pipeline using Azure services. The pipeline processes NYC payroll datasets, transforms the data, and loads it into a structured format for analysis.

---

## 🧱 Architecture

The pipeline is built using Azure Data Factory, Data Lake Storage, and Synapse Analytics.

![Pipeline Architecture](screenshots/1_pipeline_design.png)

---

## ⚙️ Technologies Used

* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2 (ADLS)
* Azure Synapse Analytics
* SQL

---

## 🔗 Linked Services

Connections were established to integrate storage and database services.

![Linked Services](screenshots/2_linked_services.png)

---

## 📂 Datasets

Multiple datasets were created to handle input and output data sources.

![Datasets](screenshots/3_datasets.png)

---

## 🔄 Dataflows

Dataflows were used to transform and process the datasets.

![Dataflows](screenshots/4_dataflows_list.png)

---

## 🔧 Data Transformation Example

Example transformation logic applied within dataflows.

![Transformation](screenshots/6_dataflow_transformation.png)

---

## 📊 SQL Output

Processed data was loaded into SQL and validated using queries.

![SQL Output](screenshots/7_sql_output.png)

---

## 📈 Synapse Output

Data successfully queried and visualized in Synapse Analytics.

![Synapse Output](screenshots/8_synapse_output.png)

---

## 🗄️ Data Lake Storage

Raw and staged data stored in Azure Data Lake.

![Data Lake](screenshots/9_data_lake.png)

---

## ✅ Pipeline Execution

Successful execution of pipeline activities in ADF Monitor.

![Pipeline Success](screenshots/10_pipeline_success.png)

---

## 🧠 Key Learnings

* Built end-to-end ETL pipeline using Azure services
* Implemented data transformations using Dataflows
* Integrated ADLS with SQL and Synapse
* Debugged real-world data pipeline errors

---

## 📁 Repository Structure

```text
README.md
screenshots/
code/
```

---

## 📌 Conclusion

This project showcases the practical implementation of a scalable cloud-based data engineering pipeline using Azure ecosystem tools.
