# 📊 UPI Transaction Analysis Dashboard

An interactive **Power BI dashboard** designed to analyze UPI transactions in India and provide insights into transaction volume, transaction value, payment methods, states, and user behavior.

## 📌 Project Overview

The **UPI Transaction Analysis Dashboard** provides a visual analysis of UPI transactions across India. The dashboard helps understand transaction trends, payment performance, geographic distribution, and the contribution of different UPI applications.

The project was developed using **Microsoft Power BI**, with data transformation, data modeling, DAX measures, and interactive visualizations.

## 🎯 Objectives

* Analyze overall UPI transaction performance.
* Track transaction volume and transaction value.
* Identify transaction trends over time.
* Compare different UPI applications/payment methods.
* Analyze state-wise transaction activity across India.
* Identify high-performing and low-performing regions.
* Provide interactive filtering for better analysis.
* Present insights through an easy-to-understand dashboard.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculations
* **Data Modeling** – Relationships between datasets
* **Microsoft Power BI Service** – Dashboard publishing and sharing
* **GitHub** – Project version control and documentation

## 📊 Dashboard Features

### 🔹 KPI Overview

The dashboard provides key performance indicators such as:

* Total Transactions
* Total Transaction Amount
* Average Transaction Value
* Transaction Growth
* Number of States/Regions Covered

### 🔹 Transaction Analysis

* Transaction volume analysis
* Transaction value analysis
* Monthly/yearly transaction trends
* Comparison of transaction performance
* Transaction amount distribution

### 🔹 UPI Application Analysis

The dashboard compares major UPI applications/payment platforms, such as:

* Google Pay
* PhonePe
* Paytm
* BHIM
* Other UPI applications

This helps identify which platforms contribute significantly to UPI transaction activity.

### 🔹 Geographic Analysis

The dashboard provides an India-focused analysis of transactions, allowing users to explore:

* State-wise transactions
* State-wise transaction value
* Regional performance
* High-performing states
* Low-performing states

### 🔹 Interactive Filters

Users can interact with the dashboard using slicers and filters to analyze specific:

* Time periods
* States
* UPI applications
* Transaction categories

## 📈 Key Insights

The dashboard can be used to identify:

* Overall growth and trends in UPI transactions.
* States with higher transaction activity.
* UPI applications with higher transaction contribution.
* Changes in transaction volume over time.
* Differences between transaction count and transaction value.
* Regional patterns in digital payment adoption.

## 🧮 DAX Measures

Several DAX measures were created to support the dashboard analysis, including calculations for:

* Total Transactions
* Total Transaction Amount
* Average Transaction Amount
* Transaction Growth
* Percentage Contribution
* Other analytical KPIs

Example:

```DAX
Total Transactions =
SUM('UPI Transactions'[Transaction Count])
```

## 🔄 Data Preparation

The data was prepared using **Power Query** before creating the dashboard.

The major data preparation steps included:

1. Importing the dataset into Power BI.
2. Removing unnecessary columns.
3. Handling missing or inconsistent values.
4. Correcting data types.
5. Creating calculated columns where required.
6. Transforming the dataset for analysis.
7. Creating relationships between tables.
8. Building the final Power BI data model.

## 🏗️ Dashboard Workflow

```text
Raw UPI Data
     ↓
Power Query
     ↓
Data Cleaning & Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Interactive Visualizations
     ↓
Power BI Dashboard
     ↓
Power BI Service
```

## ☁️ Power BI Service

The completed dashboard has been **published to Microsoft Power BI Service** for online access and sharing.

> 🔗 **Power BI Service Dashboard:**
> Add your published Power BI report link here.

Example:

```text
https://app.powerbi.com/...
```

## 📂 Project Structure

```text
UPI_Transaction_Analysis/
│
├── UPI_Transaction_Analysis.pbix
├── Dataset/
│   └── UPI_Transactions.csv
│
├── Screenshots/
│   └── dashboard.png
│
└── README.md
```

## 🖼️ Dashboard Preview

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3771ea2c-9db2-4337-bd70-356b40acb38f" />


## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/UPI_Transaction_Analysis.git
```

### 2. Open the Power BI File

Open:

```text
UPI_Transaction_Analysis.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Explore the Dashboard

Use the available slicers, filters, charts, maps, and KPIs to explore UPI transaction data.

### 4. View Online

The dashboard is also published on **Power BI Service**.

## 💡 Business Value

This dashboard demonstrates how business intelligence tools can transform raw digital-payment data into actionable insights.

It can help analysts and business stakeholders:

* Monitor payment performance.
* Identify regional trends.
* Compare payment platforms.
* Track transaction growth.
* Support data-driven decision making.

## 📚 Skills Demonstrated

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Modeling
* Data Visualization
* KPI Development
* Business Intelligence
* Dashboard Design
* Data Analysis
* Power BI Service
* Git & GitHub

## 👩‍💻 Author

**Tanzeem Hundekari**

MCA Student | Aspiring Data Analyst

### 🔗 Project

**UPI Transaction Analysis Dashboard**

Built using **Microsoft Power BI**
