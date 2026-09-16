<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E5EAA,100:00C6A7&height=220&section=header&text=Data%20Warehouse%20and%20Analytics&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=SQL%20Server%20%7C%20ETL%20%7C%20Medallion%20Architecture%20%7C%20Analytics&descAlignY=55&descSize=18" />
</p>

<p align="center">
  <a href="https://github.com/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00C6A7&center=true&vCenter=true&width=700&lines=Bronze+%E2%86%92+Silver+%E2%86%92+Gold;Raw+Data+%E2%86%92+ETL+%E2%86%92+Insights;Built+with+SQL+Server+and+T-SQL" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="#%EF%B8%8F-data-architecture"><img src="https://img.shields.io/badge/Architecture-2E5EAA?style=flat-square&logoColor=white" /></a>
  <a href="#-etl-process"><img src="https://img.shields.io/badge/ETL%20Process-1E7FA8?style=flat-square" /></a>
  <a href="#-analytics"><img src="https://img.shields.io/badge/Analytics-13A0A6?style=flat-square" /></a>
  <a href="#-repository-structure"><img src="https://img.shields.io/badge/Structure-00C6A7?style=flat-square" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/T--SQL-003B57?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/SSMS-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Draw.io-F08705?style=for-the-badge&logo=diagramsdotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />
</p>

<p align="center">
  <b>A complete Data Warehouse and Analytics solution built with SQL Server</b><br/>
  covering the full pipeline from raw source data to business-ready analytical models.
</p>

<p align="center">
  Created as a hands-on learning and portfolio project to practice<br/>
  <b>Data Engineering · ETL · Data Modeling · SQL Analytics · Warehouse Architecture</b>
</p>

<br/>

<!-- ===================== ARCHITECTURE ===================== -->

## 🏗️ Data Architecture

The project follows a **Medallion Architecture** with three layers:

<p align="center">
  <img src="https://img.shields.io/badge/🥉%20BRONZE-Raw%20Data-cd7f32?style=for-the-badge" />
  <img src="https://img.shields.io/badge/→-000000?style=for-the-badge&labelColor=ffffff00" />
  <img src="https://img.shields.io/badge/🥈%20SILVER-Clean%20Data-9ca3af?style=for-the-badge" />
  <img src="https://img.shields.io/badge/→-000000?style=for-the-badge&labelColor=ffffff00" />
  <img src="https://img.shields.io/badge/🥇%20GOLD-Star%20Schema-d4af37?style=for-the-badge" />
</p>

<p align="center">
  <img width="1544" height="912" alt="data_architecture" src="https://github.com/user-attachments/assets/d615713c-4e62-4080-96c9-92d74b13cb01" />
</p>

<details open>
<summary><b>🥉 Bronze Layer — Raw Data</b></summary>

<br/>

Raw data loaded directly from the source systems, with no business transformations applied.

| Item | Detail |
| :-- | :-- |
| **Source systems** | ERP and CRM |
| **Input format** | CSV files |
| **Storage** | SQL Server |
| **Purpose** | Preserve original source data and provide a reliable ETL starting point |

</details>

<details>
<summary><b>🥈 Silver Layer — Clean Data</b></summary>

<br/>

Prepares the raw data for analytical use.

- 🧹 Data cleansing
- 📏 Data standardization
- ✅ Data validation
- 🔀 Handling inconsistent values
- 🗑️ Removing duplicates
- 🔤 Data type corrections
- 🔗 Preparing integrated datasets

</details>

<details>
<summary><b>🥇 Gold Layer — Business-Ready Data</b></summary>

<br/>

Business-ready data designed for reporting and analytics, organized as a **Star Schema**:

- ⭐ Fact tables
- 🧩 Dimension tables
- 🏷️ Business-friendly attributes
- 📐 Analytical measures

This layer is the main source for generating insights and analytical reports.

</details>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== OVERVIEW ===================== -->

## 📖 Project Overview

The goal is to build a modern SQL Server Data Warehouse that integrates data from multiple source systems and transforms it into a structure suitable for analytical workloads.

```
Source Data  →  ETL  →  Data Warehouse  →  Data Modeling  →  Analytics
```

### Key Areas

| # | Area | What was done |
| :-: | :-- | :-- |
| 1 | 🏛️ **Data Architecture** | Structured warehouse using Bronze, Silver, and Gold layers |
| 2 | ⚙️ **ETL Pipelines** | SQL-based extract, load, clean, transform, and model |
| 3 | 🧊 **Data Modeling** | Star Schema with fact and dimension tables |
| 4 | 🛡️ **Data Quality** | Checks and transformations before data reaches the analytical layer |
| 5 | 📊 **SQL Analytics** | Queries for customer, product, and sales performance |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== OBJECTIVES ===================== -->

## 🎯 Project Objectives

```diff
+ Build a complete Data Warehouse using SQL Server
+ Integrate data from ERP and CRM systems
+ Implement a structured ETL process
+ Apply data cleansing and transformation techniques
+ Design a scalable analytical data model
+ Create business-ready datasets for reporting
+ Practice advanced SQL for analytical workloads
+ Generate meaningful insights from the integrated data
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== TOOLS ===================== -->


## 🛠️ Technologies & Tools
 
<p align="center">
  <img src="https://skillicons.dev/icons?i=mssql,git,github,markdown&theme=dark" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/SSMS-2E5EAA?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/T--SQL-2E5EAA?style=flat-square" />
  <img src="https://img.shields.io/badge/Draw.io-1E7FA8?style=flat-square&logo=diagramsdotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-1E7FA8?style=flat-square&logo=github&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/CSV-13A0A6?style=flat-square" />
  <img src="https://img.shields.io/badge/Medallion%20Architecture-13A0A6?style=flat-square" />
  <img src="https://img.shields.io/badge/Star%20Schema-00C6A7?style=flat-square" />
  <img src="https://img.shields.io/badge/ETL%20%2F%20ELT-00C6A7?style=flat-square" />
</p>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== STRUCTURE ===================== -->

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets from ERP and CRM systems
│
├── docs/                               # Project documentation and architecture
│   ├── etl.drawio                      # ETL techniques and process flow
│   ├── data_architecture.drawio        # Overall project architecture
│   ├── data_catalog.md                 # Dataset and column documentation
│   ├── data_flow.drawio                # Data movement and transformation flow
│   ├── data_models.drawio              # Data models and star schema
│   ├── naming-conventions.md           # Naming standards for the project
│
├── scripts/                            # SQL scripts for data processing
│   ├── bronze/                         # Data extraction and raw loading
│   ├── silver/                         # Data cleansing and transformation
│   ├── gold/                           # Analytical data models
│
├── tests/                              # Data quality and validation scripts
│
├── README.md                           # Project documentation
├── LICENSE                             # Project license
├── .gitignore                          # Git ignored files
└── requirements.txt                    # Project requirements
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />


<!-- ===================== ANALYTICS ===================== -->

## 📊 Analytics

The final analytical layer answers important business questions.

<table>
<tr>
<td width="33%" valign="top">

### 👥 Customer Analysis
- Purchasing behavior
- Customer segmentation
- Customer activity
- Sales contribution

</td>
<td width="33%" valign="top">

### 📦 Product Analysis
- Product performance
- Product sales
- Contribution to revenue
- Product trends

</td>
<td width="33%" valign="top">

### 💰 Sales Analysis
- Overall performance
- Trends over time
- Revenue analysis
- Customer & product performance

</td>
</tr>
</table>

> The purpose of the analytical layer is to transform raw data into **clear and useful business insights**.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== QUALITY ===================== -->

## 🧪 Data Quality & Validation

Data quality is considered throughout the pipeline.

| ✅ Check | Purpose |
| :-- | :-- |
| Missing values | Catch incomplete records early |
| Invalid data | Reject values outside expected ranges |
| Duplicate records | Keep one row per business key |
| Incorrect data types | Ensure correct casting and formats |
| Inconsistent naming | Standardize codes and labels |
| Unexpected values | Surface anomalies before modeling |
| Referential integrity | Keep facts linked to valid dimensions |

These checks help ensure that the Gold layer contains reliable data for analytics.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== LEARNED ===================== -->

## 📚 What I Practiced

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Warehouse%20Architecture-1e3a8a?style=flat-square" />
  <img src="https://img.shields.io/badge/Medallion%20Architecture-1e40af?style=flat-square" />
  <img src="https://img.shields.io/badge/ETL%20Development-1d4ed8?style=flat-square" />
  <img src="https://img.shields.io/badge/Data%20Cleaning-2563eb?style=flat-square" />
  <img src="https://img.shields.io/badge/Data%20Integration-3b82f6?style=flat-square" />
  <br/>
  <img src="https://img.shields.io/badge/Data%20Modeling-1e3a8a?style=flat-square" />
  <img src="https://img.shields.io/badge/Star%20Schema-1e40af?style=flat-square" />
  <img src="https://img.shields.io/badge/Fact%20%26%20Dimension%20Tables-1d4ed8?style=flat-square" />
  <img src="https://img.shields.io/badge/SQL%20Server-2563eb?style=flat-square" />
  <img src="https://img.shields.io/badge/T--SQL-3b82f6?style=flat-square" />
  <br/>
  <img src="https://img.shields.io/badge/Advanced%20SQL-1e3a8a?style=flat-square" />
  <img src="https://img.shields.io/badge/Data%20Quality%20Testing-1e40af?style=flat-square" />
  <img src="https://img.shields.io/badge/Analytical%20SQL-1d4ed8?style=flat-square" />
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-2563eb?style=flat-square" />
  <img src="https://img.shields.io/badge/Technical%20Documentation-3b82f6?style=flat-square" />
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== SCOPE ===================== -->

## 📌 Project Scope

> The project focuses on the **latest available dataset** from the source systems.
>
> Historical data tracking and full historization are **outside the current scope**.
>
> The main focus is building a clean, integrated, and analytical data warehouse that can support business reporting and analysis.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== AUTHOR ===================== -->

## 👨‍💻 Author

<p align="center">
  <b>Mahmoud Fawzy</b><br/>
  <i>Data Analyst · Data Engineering & Analytics Enthusiast</i>
</p>

I built this project as part of my journey in learning **Data Engineering, Data Warehousing, SQL, and Analytics**.

The project was developed as a hands-on implementation while following the educational material and project guidance provided by **Eng. Baraa Khatib Salkini (Data With Baraa)**.

A special thanks to **Eng. Baraa** for creating the educational content and sharing practical knowledge about Data Warehousing, SQL, ETL, and Data Analytics.

This project is my own learning implementation, with modifications and documentation adapted to my learning journey and portfolio.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<!-- ===================== LICENSE ===================== -->

## 📄 License

This project is available under the **MIT License**.
You are free to use, modify, and build upon the project according to the terms of the license.

<br/>

<p align="center">
  <a href="https://github.com/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=00C6A7&center=true&vCenter=true&width=650&lines=Thanks+for+reading!;Star+the+repo+if+it+helped+you+%E2%AD%90;Built+by+Mahmoud+Fawzy" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="#-data-warehouse-and-analytics-project"><img src="https://img.shields.io/badge/Back%20to%20Top-2E5EAA?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Made%20with-SQL%20Server-1E7FA8?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-00C6A7?style=flat-square" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C6A7,100:2E5EAA&height=180&section=footer&text=Source%20to%20Insight&fontSize=28&fontColor=ffffff&animation=fadeIn&fontAlignY=78&desc=Bronze%20%7C%20Silver%20%7C%20Gold&descAlignY=95&descSize=14" />
</p>
