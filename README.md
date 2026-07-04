# ☁️ End-to-End Azure SQL Database Analytics using Power BI

An end-to-end Business Intelligence project demonstrating how **Azure SQL Database**, **SQL Server Management Studio (SSMS)**, **Power BI Desktop**, and **Power BI Service** work together to build a cloud-based analytics solution.

The project follows a practical enterprise workflow where raw business data is uploaded to Azure SQL Database, cleaned using SQL, connected to Power BI Desktop for reporting, and finally deployed to Power BI Service as a shareable Power BI App.

---

# 📌 Business Problem

Organizations increasingly store operational data in cloud-hosted databases instead of local servers. Business analysts require a centralized, secure, and scalable data source that can be accessed from anywhere while supporting reporting, collaboration, and deployment.

The objective of this project is to demonstrate how Azure SQL Database can serve as the cloud data source for an end-to-end reporting solution using Power BI.

---

# ✅ Solution

This project implements a complete cloud reporting workflow by:

- Creating an Azure SQL Database and SQL Server.
- Connecting SQL Server Management Studio (SSMS) to Azure SQL.
- Importing CSV data into Azure SQL Database.
- Performing SQL-based data cleaning and preparation.
- Connecting Power BI Desktop directly to Azure SQL Database.
- Applying additional transformations using Power Query.
- Creating calculated columns and business measures using DAX.
- Designing an interactive two-page Power BI report.
- Publishing the report to Power BI Service.
- Creating a Power BI Workspace and deploying the report as a Power BI App.

---

# 🔄 End-to-End Project Workflow

```text
CSV Dataset
      │
      ▼
Azure SQL Database
      │
      ▼
SQL Data Cleaning
      │
      ▼
Power BI Desktop
      │
      ▼
Power Query
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Publish to Power BI Service
      │
      ▼
Workspace
      │
      ▼
Power BI App
```

---

# 🏗️ Architecture

```
CSV File
    │
    ▼
Azure SQL Database
    │
    ▼
SQL Cleaning & Validation
    │
    ▼
Power BI Desktop
    │
    ▼
Power Query
    │
    ▼
DAX Measures
    │
    ▼
Interactive Report
    │
    ▼
Power BI Service
    │
    ▼
Workspace
    │
    ▼
Power BI App
```

---

# 🛠️ Technologies Used

- Microsoft Azure SQL Database
- Azure SQL Server
- SQL Server Management Studio (SSMS)
- Microsoft SQL
- Power BI Desktop
- Power Query
- DAX
- Power BI Service
- Power BI Workspace
- Power BI App

---

# ⭐ Project Highlights

- Created a cloud-hosted Azure SQL Database.
- Configured Azure SQL Server connectivity.
- Connected SSMS to Azure SQL Database.
- Imported CSV dataset into Azure SQL.
- Cleaned and transformed data using SQL.
- Connected Power BI Desktop to Azure SQL Database.
- Performed additional transformations using Power Query.
- Built calculated columns and business metrics using DAX.
- Designed an interactive two-page Power BI report.
- Published the report to Power BI Service.
- Created a dedicated Workspace.
- Built and deployed a Power BI App.
- Demonstrated an end-to-end cloud reporting workflow.

---

# 📂 Repository Structure

```
azure-sql-database-powerbi-analysis
│
├── Azure PowerBi Report.pbix
├── Men+Tshirt.csv
├── README.md
│
└── screenshots
    ├── dashboard.png
    ├── data_cleaning_at_azure_query_editor.png
    ├── loading_data_from_azure_sql_to_powerbi_desktop.png
    ├── publish_powerbi_app.png
    ├── publish_to_powerbi_services.png
    └── sql_azure_connection.png
```

---

# ⚙️ Implementation Steps

## Step 1 — Azure SQL Database Setup

- Created a new Azure SQL Server.
- Created a dedicated Azure SQL Database.
- Configured firewall rules.
- Generated server credentials.

---

## Step 2 — Data Import

- Connected SSMS with Azure SQL Server.
- Imported the CSV dataset.
- Created the required database table.

---

## Step 3 — SQL Data Cleaning

Performed data preparation using SQL including:

- Data validation
- Data cleaning
- Null handling
- Standardization
- Basic transformations

---

## Step 4 — Power BI Desktop

- Connected Power BI Desktop to Azure SQL Database.
- Loaded the cleaned dataset.
- Built the data model.

---

## Step 5 — Data Transformation

Performed additional transformations using Power Query.

Created:

- Custom Columns
- Conditional Columns
- Data Type Formatting
- Query Transformations

---

## Step 6 — Dashboard Development

Developed a two-page interactive Power BI report using:

- KPI Cards
- Charts
- Slicers
- DAX Measures
- Business Insights

---

## Step 7 — Deployment

- Published the report to Power BI Service.
- Created a Workspace.
- Deployed the report as a Power BI App.

---

# 📸 Project Screenshots

## Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Azure SQL Connection

![Azure SQL Connection](screenshots/sql_azure_connection.png)

---

## SQL Data Cleaning

![SQL Cleaning](screenshots/data_cleaning_at_azure_query_editor.png)

---

## Loading Azure SQL into Power BI

![Power BI Connection](screenshots/loading_data_from_azure_sql_to_powerbi_desktop.png)

---

## Publishing to Power BI Service

![Power BI Service](screenshots/publish_to_powerbi_services.png)

---

## Power BI App

![Power BI App](screenshots/publish_powerbi_app.png)

---

# 💼 Skills Demonstrated

- Azure SQL Database
- Cloud Database Management
- SQL
- SQL Server Management Studio
- Data Cleaning
- Power Query
- DAX
- Power BI Desktop
- Power BI Service
- Workspace Management
- Power BI App Deployment
- Dashboard Development
- Data Transformation
- Business Intelligence
- Cloud Analytics

---

# 📦 Project Deliverables

- Azure SQL Database Setup
- SQL Data Cleaning
- Interactive Power BI Dashboard
- Power BI Desktop Report (.pbix)
- Power BI Service Deployment
- Power BI App
- Project Documentation

---

# 🎯 Learning Outcomes

This project strengthened my practical understanding of:

- Azure SQL Database
- Cloud-hosted Relational Databases
- SQL Data Cleaning
- Power BI Desktop
- Power Query
- DAX
- Power BI Service
- Workspace Management
- Power BI App Deployment
- End-to-End Cloud Reporting Workflow

---

# 🚀 Future Enhancements

- Implement Row-Level Security (RLS)
- Configure Scheduled Refresh
- Connect Azure Data Factory
- Integrate Azure Blob Storage
- Build Incremental Refresh
- Create Deployment Pipelines
- Add Multiple Data Sources

---

# 👨‍💻 Author

**Sagar Bairwa**

- GitHub: https://github.com/sagar-bairwa
- LinkedIn: https://linkedin.com/in/sagarbairwa

⭐ If you found this project helpful, consider giving it a star.