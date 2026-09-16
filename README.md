# 🏢 Data Warehouse and Analytics Project

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2E86C1&center=true&vCenter=true&width=600&lines=Modern+Data+Warehouse+with+SQL+Server;Medallion+Architecture+%7C+Bronze+%E2%86%92+Silver+%E2%86%92+Gold;ETL+Pipelines+%7C+Data+Modeling+%7C+Analytics" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/DE-MahmoudF/data-warehouse-project?style=for-the-badge&color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/DE-MahmoudF/data-warehouse-project?style=for-the-badge&color=blue" alt="Forks"/>
  <img src="https://img.shields.io/github/issues/DE-MahmoudF/data-warehouse-project?style=for-the-badge&color=orange" alt="Issues"/>
  <img src="https://img.shields.io/github/last-commit/DE-MahmoudF/data-warehouse-project?style=for-the-badge&color=brightgreen" alt="Last Commit"/>
  <img src="https://img.shields.io/github/license/DE-MahmoudF/data-warehouse-project?style=for-the-badge&color=purple" alt="License"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DE-MahmoudF&style=for-the-badge&color=blueviolet&label=Repo+Views" alt="Profile Views"/>
</p>

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive, end-to-end data warehousing and analytics solution — from building a data warehouse from scratch to generating actionable business insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture**: Bronze, Silver, and Gold layers.

| Layer | Purpose |
|---|---|
| 🥉 **Bronze** | Stores raw data as-is from source systems. Data is ingested from CSV files into a SQL Server database. |
| 🥈 **Silver** | Includes data cleansing, standardization, and normalization to prepare data for analysis. |
| 🥇 **Gold** | Houses business-ready data modeled into a star schema, ready for reporting and analytics. |

---

## 📖 Project Overview

This project involves:

- **🏛️ Data Architecture** — Designing a modern data warehouse using Bronze, Silver, and Gold layers.
- **🔄 ETL Pipelines** — Extracting, transforming, and loading data from source systems into the warehouse.
- **📐 Data Modeling** — Developing fact and dimension tables optimized for analytical queries.
- **📊 Analytics & Reporting** — Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

`SQL Development` • `Data Architecture` • `Data Engineering` • `ETL Pipeline Development` • `Data Modeling` • `Data Analytics`

---

## 🛠️ Important Links & Tools

Everything used in this project is **completely free**:

| Tool | Purpose |
|---|---|
| 📂 [Datasets](#) | Project dataset (CSV files) |
| 🖥️ [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) | Lightweight server for hosting your SQL database |
| 🧰 [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms) | GUI for managing and interacting with databases |
| 🐙 [GitHub](https://github.com) | Version control and collaboration |
| 🎨 [Draw.io](https://app.diagrams.net/) | Design architecture, models, flows, and diagrams |
| 📓 [Notion](https://notion.so) | Project template and task tracking |

---

## 🚀 Project Requirements

### 1️⃣ Building the Data Warehouse (Data Engineering)

**Objective**
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**
- **Data Sources:** Import data from two source systems (ERP and CRM), provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only — historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### 2️⃣ BI: Analytics & Reporting (Data Analysis)

**Objective**
Develop SQL-based analytics to deliver detailed insights into:

- 👥 Customer Behavior
- 📦 Product Performance
- 📈 Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

📄 For more details, refer to [`docs/requirements.md`](docs/requirements.md).

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing ETL techniques and methods
│   ├── data_architecture.drawio        # Draw.io file showing the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DE-MahmoudF&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Mahmoud Fawzy's GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DE-MahmoudF&theme=tokyonight&hide_border=true" alt="Streak Stats" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DE-MahmoudF&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>

Hi there! I'm **Mahmoud Fawzy**, a Data Engineer passionate about building clean, reliable, and scalable data pipelines. This project is part of my portfolio, showcasing hands-on experience with modern data warehousing practices — from raw ingestion to business-ready analytics.

📫 **Let's connect!**

<p align="center">
  <a href="https://github.com/DE-MahmoudF">
    <img src="https://img.shields.io/badge/GitHub-DE--MahmoudF-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

---

<p align="center">⭐ If you found this project helpful, consider giving it a star — it really helps! ⭐</p>
