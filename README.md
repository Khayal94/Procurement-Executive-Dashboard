# 📊 Procurement Executive Dashboard

![Procurement Executive Dashboard](screenshots/dashboard_overview.png)

> **An end-to-end Business Intelligence project demonstrating procurement analytics using Python, SQL Server, SQL Views, DAX, and Power BI.**

---

# 🚀 Project Overview

The Procurement Executive Dashboard is a portfolio project designed to simulate a real-world procurement analytics environment.

The project demonstrates the complete Business Intelligence workflow—from synthetic data generation to executive-level reporting—using modern data analytics technologies.

The dashboards help procurement managers and executives monitor procurement spending, supplier performance, delivery efficiency, and sustainability (ESG) metrics to support strategic business decisions.

---

# 🎯 Business Problem

Procurement departments manage hundreds of suppliers, thousands of purchase orders, and significant procurement spending.

Without a centralized reporting solution, it is difficult to:

- Monitor procurement spending
- Evaluate supplier performance
- Track delivery reliability
- Measure ESG performance
- Identify high-risk suppliers
- Support executive decision-making

This project addresses these challenges by transforming raw procurement data into interactive Power BI dashboards.

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Synthetic procurement data generation |
| Pandas | Data preparation |
| SQL Server | Database |
| SQL Views | Reporting layer |
| Power BI | Dashboard development |
| DAX | KPI calculations |
| GitHub | Version control |

---

# 📂 Repository Structure

```
Procurement-Executive-Dashboard
│
├── data
│   ├── raw
│   └── processed
│
├── sql
│
├── python
│
├── powerbi
│
├── screenshots
│
├── documentation
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
(Business Layer)
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

The project includes the following datasets:

- Countries
- Suppliers
- Products
- Purchase Orders
- Deliveries
- Sustainability

Business reporting is built on SQL Views:

- vw_CountryProcurement
- vw_SupplierPerformance
- vw_DeliveryPerformance
- vw_SustainabilityOverview

---

# 📊 Dashboard Pages

## 📈 Executive Overview

![Executive Overview](screenshots/executive_overview.png)

The Executive Overview dashboard provides a high-level summary of procurement performance.

### KPIs

- Total Procurement Spend
- Total Suppliers
- Average ESG Score
- Late Delivery Rate
- Spend at Risk
- High-Risk Suppliers

Key analyses include:

- Procurement Spend Trend
- Spend by Country
- Supplier Risk Matrix
- Top Suppliers by Spend
- Worst Suppliers by Late Delivery
- Executive Insights

---

## 🤝 Supplier Performance

![Supplier Performance](screenshots/supplier_performance.png)

This dashboard focuses on supplier evaluation.

Features include:

- Supplier Scorecard
- Procurement Ranking
- Delivery Performance
- Supplier Health Score
- Pareto Analysis
- Monthly Delivery Trends

---

## 🌱 ESG & Sustainability Analytics

![ESG Dashboard](screenshots/esg_dashboard.png)

This dashboard supports sustainability monitoring.

Included analyses:

- ESG Score Distribution
- Sustainability Risk Treemap
- CO₂ Emissions by Country
- CO₂ Emissions by Industry
- Top ESG Suppliers
- ESG Risk Matrix

---

# 📈 Key Performance Indicators

The dashboard tracks several business KPIs:

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

The dashboards enable procurement managers to:

- Identify high-performing suppliers
- Detect delivery issues
- Monitor procurement spending
- Compare supplier ESG performance
- Reduce procurement risks
- Support strategic sourcing decisions

---

# 📸 Dashboard Preview

| Dashboard | Description |
|-----------|-------------|
| Executive Overview | Executive KPIs and procurement insights |
| Supplier Performance | Supplier evaluation and operational analysis |
| ESG & Sustainability | Sustainability and environmental performance |

---

# 🚀 Future Improvements

Future enhancements may include:

- Real ERP procurement data
- Predictive supplier risk modeling
- Machine Learning for delivery prediction
- Automated Power BI refresh
- Row-Level Security (RLS)
- Procurement forecasting
- Azure SQL integration

---

# ▶️ How to Run the Project

1. Run the Python notebook to generate procurement datasets.
2. Import CSV files into SQL Server.
3. Execute the SQL scripts to create tables and views.
4. Open the Power BI (.pbix) file.
5. Refresh the data model.

---

# 👨‍💻 Author

**Khayal Dadashzade**

Business Analyst | Data Analyst | Power BI Developer

GitHub: https://github.com/Khayal94

LinkedIn:
(Add your LinkedIn profile)

---

# ⭐ Project Status

**Completed**

This project was developed as part of my data analytics portfolio to demonstrate end-to-end Business Intelligence development using Python, SQL Server, DAX, and Power BI.
