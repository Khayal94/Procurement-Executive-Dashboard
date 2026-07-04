# 📊 Procurement Executive Dashboard

![Dashboard Overview](screenshots/dashboard_overview.png)

> **An end-to-end Business Intelligence project demonstrating procurement analytics using Python, SQL Server, SQL Views, DAX, and Power BI.**

---

# 🚀 Project Overview

The Procurement Executive Dashboard is an end-to-end Business Intelligence project that simulates a real-world procurement analytics environment.

The project demonstrates the complete analytics workflow—from synthetic data generation in Python to SQL Server database design and interactive Power BI dashboards.

The dashboards enable procurement managers and executives to monitor procurement spending, supplier performance, delivery reliability, and ESG (Environmental, Social, and Governance) metrics to support strategic business decisions.

---

# 🎯 Business Problem

Modern procurement departments manage hundreds of suppliers and thousands of purchase orders.

Without centralized reporting, it becomes difficult to:

- Monitor procurement spending
- Evaluate supplier performance
- Identify delivery issues
- Measure ESG performance
- Detect high-risk suppliers
- Support executive decision-making

This project addresses these challenges through interactive dashboards built in Power BI.

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Synthetic Data Generation |
| Pandas | Data Preparation |
| SQL Server | Database |
| SQL Views | Reporting Layer |
| Power BI | Dashboard Development |
| DAX | KPI Calculations |
| Git | Version Control |
| GitHub | Project Repository |

---

# 📂 Repository Structure

```
Procurement-Executive-Dashboard
│
├── data
│   ├── raw
│   └── processed
│
├── documentation
│
├── powerbi
│   └── Procurement_Executive_Dashboard.pbix
│
├── python
│   └── Procurement_Data_Generation.ipynb
│
├── screenshots
│   └── dashboard_overview.png
│
├── sql
│
└── README.md
```

---

# 🏗 Solution Architecture

```
Python
(Data Generation)
        │
        ▼
CSV Files
        │
        ▼
SQL Server
(Database)
        │
        ▼
SQL Views
(Business Reporting Layer)
        │
        ▼
Power BI
(Dashboard & DAX)
        │
        ▼
Executive Decision Making
```

---

# 🗄 Database

The project includes six procurement datasets:

- Countries
- Suppliers
- Products
- Purchase Orders
- Deliveries
- Sustainability

Business reporting is built on SQL Views including:

- vw_CountryProcurement
- vw_SupplierPerformance
- vw_DeliveryPerformance
- vw_SustainabilityOverview

---

# 📊 Dashboard Pages

## Executive Overview

Provides executives with an overall view of procurement performance.

### KPIs

- Total Procurement Spend
- Total Suppliers
- Average ESG Score
- Late Delivery Rate
- Spend at Risk
- High-Risk Suppliers

Additional analyses include:

- Procurement Spend Trend
- Country Analysis
- Supplier Risk Matrix
- Top Suppliers by Spend
- Worst Suppliers by Late Delivery
- Executive Insights

---

## Supplier Performance

Provides operational supplier analytics including:

- Supplier Scorecards
- Procurement Ranking
- Delivery Performance
- Health Score
- Pareto Analysis
- Monthly Delivery Trends

---

## ESG & Sustainability Analytics

Supports sustainability monitoring through:

- ESG Score Distribution
- Sustainability Risk Analysis
- CO₂ Emissions
- ESG Performance
- High-Risk Supplier Monitoring

---

# 📈 Key Performance Indicators

The dashboard monitors:

- Total Procurement Spend
- Total Suppliers
- Average ESG Score
- Late Delivery Rate
- Spend at Risk
- High-Risk Suppliers
- Supplier Health Score
- Total CO₂ Emissions

---

# 💡 Business Insights

This dashboard enables decision-makers to:

- Identify top-performing suppliers
- Detect suppliers with delivery problems
- Monitor procurement spending
- Evaluate supplier sustainability performance
- Prioritize supplier risk mitigation
- Improve procurement strategy

---

# 📸 Dashboard Preview

The Power BI solution consists of three interactive dashboards:

- Executive Overview
- Supplier Performance
- ESG & Sustainability Analytics

The dashboard preview is shown below.

![Dashboard Preview](screenshots/dashboard_overview.png)

---

# 🚀 Future Improvements

Potential future enhancements include:

- Integration with ERP procurement systems
- Machine Learning models for supplier risk prediction
- Automated Power BI Service refresh
- Row-Level Security (RLS)
- Procurement forecasting
- Azure SQL Database integration

---

# ▶️ How to Run

1. Run the Python notebook to generate procurement datasets.
2. Import CSV files into SQL Server.
3. Execute the SQL scripts.
4. Create SQL Views.
5. Open the Power BI (.pbix) report.
6. Refresh the data model.

---

# 👨‍💻 Author

**Khayal Dadashzade**

Business Analyst | Data Analyst | Power BI Developer

**GitHub**

https://github.com/Khayal94

**LinkedIn**

(Add your LinkedIn profile URL)

---

# ⭐ Project Status

✅ Completed

This project was developed as part of my Business Intelligence and Data Analytics portfolio to demonstrate end-to-end analytics development using Python, SQL Server, SQL Views, DAX, and Power BI.
