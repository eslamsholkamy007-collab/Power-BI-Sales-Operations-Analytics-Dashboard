# 📊 Power BI Sales & Operations Analytics Dashboard

## 🚀 Project Overview

This project is an **End-to-End Data Analytics and Business Intelligence solution** built using **Microsoft Power BI**.

The project started with **25 separate raw CSV files** containing data from different business processes. The main challenge was not only building the dashboard, but also transforming, cleaning, validating, and modeling the raw data into a reliable and scalable data model.

The final result is a **professional and interactive Power BI dashboard** designed to provide meaningful business insights and support data-driven decision-making.

> **A beautiful dashboard is only the final layer. The real work starts with understanding, cleaning, transforming, and modeling the data behind it.**

---

## 🎯 Project Objectives

The main objectives of this project were:

* Transform 25 raw CSV files into structured and analysis-ready datasets.
* Improve data quality and consistency.
* Build a reliable and scalable data model.
* Create relationships between multiple Fact and Dimension tables.
* Handle missing and inconsistent data.
* Create dedicated Date and Time dimensions.
* Develop a professional and interactive Power BI dashboard.
* Provide meaningful insights through KPIs and visualizations.

---

# 🔄 Data Preparation & ETL

A significant part of this project focused on **Data Cleaning and ETL using Power Query**.

### 🧹 Data Cleaning

The following data quality issues were handled:

* Standardized inconsistent values across multiple datasets.
* Removed unnecessary and unused columns.
* Handled missing values.
* Corrected inconsistent date formats.
* Converted dates into a standardized format.
* Separated **Date** and **Time** into independent fields.
* Converted Arabic AM/PM time values into a consistent time format.
* Assigned the correct data type to each column.
* Converted columns into appropriate formats such as:

  * Text
  * Whole Number
  * Decimal Number
  * Date
  * Time

---

# 🏗️ Data Modeling

After completing the data cleaning process, the datasets were transformed into a structured Power BI data model.

### 🔑 Unique Keys

Unique codes were created for:

* Customers
* Products

These keys were then used to establish reliable relationships between different datasets.

### 🔗 Merge Queries

Multiple datasets were connected using the generated unique keys rather than relying on duplicated names or text fields.

This helped improve:

* Data consistency
* Relationship accuracy
* Model reliability

### ➕ Append Queries

During the modeling process, some products were found to be missing from the Product Dimension.

These missing products were identified and added to the appropriate Dimension Table using **Append Queries**.

This helped maintain data completeness and improve referential integrity.

---

# 📅 Date & Time Dimensions

Dedicated Date and Time tables were created to support time-based analysis.

### Date Dimension

The Date table includes fields such as:

* Date
* Year
* Quarter
* Month
* Month Number
* Day
* Week Number

### Time Dimension

The Time table was created to enable analysis by:

* Hour Number
* Hour Name
* AM / PM
* Time-based business activity

This structure makes the model more suitable for time intelligence and operational analysis.

---

# 📐 Data Model

The project follows data modeling best practices by separating business data into **Fact Tables and Dimension Tables**.

### Dimension Tables

Examples include:

* Customer Dimension
* Product Dimension
* Date Dimension
* Time Dimension

### Fact Tables

The model contains multiple transactional and operational datasets related to areas such as:

* Sales
* Purchases
* Collections
* Expenses
* Inventory
* Customer balances
* Product transactions

The relationships between these tables were designed to support flexible and accurate reporting.

---

# 📊 Power BI Dashboard

After completing the ETL and data modeling stages, I developed a **professional and interactive Power BI dashboard**.

The dashboard focuses on transforming the underlying data into clear and actionable business insights.

### Dashboard Features

* Interactive KPI Cards
* Sales Analysis
* Purchase Analysis
* Customer Analysis
* Product Analysis
* Financial Metrics
* Time-based Analysis
* Interactive Filters and Slicers
* Dynamic Visualizations
* Drill-down analysis
* Business performance monitoring

The dashboard was designed with a focus on **UI/UX, usability, clarity, and business storytelling**.

---

# 🛠️ Tools & Technologies

| Tool              | Purpose                                    |
| ----------------- | ------------------------------------------ |
| **Power BI**      | Data visualization & dashboard development |
| **Power Query**   | Data cleaning & ETL                        |
| **DAX**           | Measures & calculations                    |
| **CSV**           | Raw data source                            |
| **Data Modeling** | Relationships & analytical structure       |
| **Excel**         | Data inspection and validation             |

---

# 🔍 Key Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* ETL
* Power Query
* Data Modeling
* Star Schema
* Fact & Dimension Tables
* Merge Queries
* Append Queries
* Data Validation
* Missing Value Handling
* Data Type Transformation
* Unique Key Creation
* Date & Time Modeling
* DAX
* Power BI Dashboard Development
* Data Visualization
* UI/UX for Business Intelligence
* Business Analysis

---

# 💡 Key Takeaway

One of the biggest lessons from this project was that:

> **Data Analytics is not just about creating charts. It's about turning raw, inconsistent data into reliable information that businesses can trust.**

Working with **25 separate CSV files** required extensive data cleaning, transformation, validation, and modeling before building the final dashboard.

This project strengthened my understanding of the complete analytics workflow:

**Raw Data → Data Cleaning → ETL → Data Modeling → DAX → Visualization → Business Insights**

---

# 📁 Project Structure

```text
PowerBI-Sales-Analytics/
│
├── Data/
│   └── CSV Files/
│
├── PowerBI/
│   └── Sales_Analytics.pbix
│
└── README.md
```

---

# 👨‍💻 About the Project

This project was developed as part of my continuous journey in **Data Analytics and Business Intelligence**, with a strong focus on practical problem-solving, data quality, and building business-ready analytical solutions.

### 📌 Core Stack

**Power BI | Power Query | DAX | Data Modeling | ETL | Data Cleaning | CSV | Data Visualization | Business Intelligence**

---

⭐ If you find this project interesting, feel free to explore the repository and connect with me.
