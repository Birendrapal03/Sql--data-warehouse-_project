# Data warehouse and Analytics Project

Welcome to the ** Data warehouse and Analytics Project ** repository 
This project demonstrates a comprehension data warehousing and analytics solution , from building a data warehouse to generating actionable insights . Designed as a portfolio project highlight best industry practices in data engineering and analytics.

---
## project Requirements

### Building the Data Warehouse (Data Engineering)

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---
**Data Architecture**
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture
<img width="1365" height="760" alt="image" src="https://github.com/user-attachments/assets/34047523-7bfd-4280-8433-0abe3dcb00b8" />
Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.




### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---
**📂 Repository Structure**
<img width="987" height="597" alt="image" src="https://github.com/user-attachments/assets/960151cf-2755-45e9-91f4-0cd7d29c589f" />



## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🧩 About Me

Hi there! I'm **Baraa Khatib Salkini**, also known as **Data With Baraa**. I'm an IT professional and passionate YouTuber on a mission to share knowledge...
