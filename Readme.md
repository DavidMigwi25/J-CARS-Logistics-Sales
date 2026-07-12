# J-CARS Logistics Sales

![Dashboard](Screenshots/Dashboard.png)

## Project Objective

The objective of this project was to develop an interactive Power BI dashboard to analyze J-CARS Logistics sales performance. The dashboard provides insights into revenue, profitability, vehicle performance, regional sales, and customer satisfaction to support business decision-making.

---

## Project Workflow

```text
Raw Excel Data
      │
      ▼
Import into PostgreSQL (Aiven) using DBeaver
      │
      ▼
Connect Power BI to PostgreSQL
      │
      ▼
Clean & Transform Data (Power Query)
      │
      ▼
Create DAX Measures
      │
      ▼
Build Interactive Dashboard
      │
      ▼
Generate Business Insights
```

---

## Data Import

The raw dataset was imported into an Aiven PostgreSQL database using DBeaver. PostgreSQL was used as the data source for Power BI.

---

## Power BI Connection

Power BI was connected directly to the PostgreSQL database using the PostgreSQL connector. The sales data was then imported for analysis.

---

## Data Cleaning

Data cleaning was performed in **Power Query** and included:

- Removing duplicates
- Correcting data types
- Handling blank values
- Renaming columns
- Preparing the dataset for analysis

---

## DAX Measures Created

The following measures were created:

- Total Revenue
- Total Orders
- Units Sold
- Total Cost
- Gross Profit
- Average Delivery Days
- Average Customer Rating

---

## Dashboard Visuals

The dashboard includes:

- KPI Cards
- Revenue Trend (Line Chart)
- Revenue by Region (Bar Chart)
- Top 10 Car Models
- Revenue vs Gross Profit
- Revenue by Vehicle Type (Donut Chart)
- Interactive Slicers
- Executive Insights

---

## Key Insights

- Revenue exceeded **KES 1 Billion** during the reporting period.
- Prado TX was the top-performing vehicle model.
- Rift Valley recorded the highest regional revenue.
- Average customer rating was approximately **4.0/5**.
- Average delivery time was approximately **25 days**.

---

## Recommendations

- Increase inventory for high-performing vehicle models.
- Improve delivery efficiency to reduce delivery time.
- Focus marketing efforts on high-performing regions and vehicle categories.
- Continue monitoring sales and profitability using the dashboard.

---

## Tools Used

- PostgreSQL (Aiven)
- DBeaver
- Power BI Desktop
- Power Query
- DAX
- GitHub