
# Data Warehouse and Analytics Project

Welcome to my **Data Warehouse and Analytics Project** repository! 🚀

This project presents an end-to-end modern data warehousing solution — starting from raw data ingestion to generating meaningful business insights. It is designed as a portfolio project to demonstrate my hands-on expertise in **Data Engineering, SQL Development, and Analytics** while following industry best practices.

---

## 👨‍💻 About Me

Hi, I’m **Manan** — a Data Enthusiast with a strong interest in Data Engineering, Analytics, and building scalable data systems.

I enjoy designing structured data solutions, optimizing SQL queries, and transforming raw datasets into actionable insights. This project reflects my ability to architect, build, and document a complete data warehouse solution using modern design principles.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach using **Bronze, Silver, and Gold layers**:

!(docs/data_architecture.png)

### 🔹 Bronze Layer

* Stores raw data exactly as received from source systems.
* Data is ingested from CSV files into SQL Server.
* No transformations are applied at this stage.

### 🔹 Silver Layer

* Performs data cleansing, transformation, normalization, and validation.
* Ensures data quality and consistency.
* Prepares structured datasets for analytical modeling.

### 🔹 Gold Layer

* Contains business-ready, analytics-optimized data.
* Implements a **Star Schema** design (Fact and Dimension tables).
* Supports reporting and decision-making processes.

---

## 📖 Project Overview

This project covers the complete lifecycle of building a modern data warehouse:

1. **Data Architecture Design**
   Designed a scalable data warehouse using Medallion Architecture (Bronze, Silver, Gold).

2. **ETL Development**
   Built structured ETL pipelines to extract, transform, and load data into the warehouse.

3. **Data Modeling**
   Developed optimized fact and dimension tables for analytical workloads.

4. **Analytics & Reporting**
   Created SQL-based reports to derive meaningful business insights.

---

## 🎯 Skills Demonstrated

This project highlights my capabilities in:

* SQL Development
* Data Engineering
* ETL Pipeline Design
* Data Modeling (Star Schema)
* Data Cleaning & Transformation
* Business Analytics

---

## 🛠️ Tools & Technologies Used

* **SQL Server Express** – Database engine
* **SQL Server Management Studio (SSMS)** – Querying & administration
* **CSV Files** – Source datasets
* **Draw.io** – Architecture and data model diagrams
* **Git & GitHub** – Version control and repository management

---

## 🚀 Project Requirements

### 🏗️ Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern SQL Server data warehouse that consolidates ERP and CRM sales data to enable structured analytical reporting.

#### Specifications

* **Data Sources**: Two systems (ERP and CRM) provided as CSV files
* **Data Quality Handling**: Clean and resolve inconsistencies before analysis
* **Integration**: Merge both systems into a unified analytical data model
* **Scope**: Focus on the latest available dataset (no historical tracking required)
* **Documentation**: Provide clear technical documentation for business and analytics users

---

### 📊 BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop SQL-driven analytics to generate insights related to:

* Customer Behavior
* Product Performance
* Sales Trends

These insights help stakeholders make informed, data-driven decisions.

---

## 📂 Repository Structure

```
sql-data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Documentation & architecture files
│   ├── data_architecture.drawio        # Overall architecture diagram
│   ├── data_catalog.md                 # Dataset metadata & descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema data models
│   ├── naming-conventions.md           # Naming standards for objects
│
├── scripts/                            # SQL scripts
│   ├── bronze/                         # Raw data ingestion
│   ├── silver/                         # Data cleaning & transformations
│   ├── gold/                           # Analytical modeling scripts
│
├── tests/                              # Data quality & validation scripts
│
├── README.md                           # Project documentation
├── LICENSE                             # License file
└── requirements.txt                    # Dependencies (if applicable)
```

---

## 🌟 Why This Project Matters

This repository demonstrates:

* End-to-end data warehouse implementation
* Real-world ETL development practices
* Structured and scalable data architecture
* Business-aligned analytics modeling

It reflects my ability to think architecturally, implement technically, and document professionally.

---

## 🛡️ License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it with proper attribution.

---
