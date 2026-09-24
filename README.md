# Power-BI-Project
# 🚲 Adventure Works Sales Analytics: Power BI Dashboard

An interactive Power BI report that analyzes **$29.4M in Adventure Works sales** across 5 years, 10 sales regions and 18,000+ customers. It uses a star-schema data model to track revenue, production cost and profit, and to show seasonality, top products and regional performance in a single Executive Dashboard.



## 🎯 Business Problem

Adventure Works sells bikes, components, clothing and accessories worldwide, and its sales data sits in separate fact and dimension tables. Leadership needs quick answers to questions like:

- What are our total sales, production cost and profit?
- How do sales change by year, quarter and month?
- Which products and regions drive the most revenue?
- Who are our highest-value customers?

## ✅ Goal of the Report

To combine the sales data into one clean model and deliver an interactive Executive Dashboard that:

- Shows headline KPIs in one glance
- Reveals yearly growth and monthly seasonality
- Compares sales against production cost
- Lets users slice every visual by **Year** and **Quarter**

---

## 🛠️ Tech Stack

- 📊 **Power BI Desktop**: report and dashboard creation
- 📂 **Power Query**: importing the data and appending two sales tables into one fact table
- 🧠 **Data Modeling**: star schema with one-to-many relationships between the fact and dimension tables
- 🧮 **DAX**: calculated columns and measures (Net Sales, Production Cost, Profit)
- 🎚️ **Slicers**: interactive filtering by Year and Quarter

## 🗂️ Data Model

| Table | Type | Contents |
|---|---|---|
| `Fact Sales Appended` | Fact | Combined sales order lines with net sales and production cost |
| `DimProduct` | Dimension | Product names, categories and costs |
| `Dimcustomer` | Dimension | Customer details and full name |
| `DimDate` | Dimension | Calendar table (year, quarter, month) |
| `DimSalesTerritory` | Dimension | Sales regions, countries and groups |

---

## 📊 Dashboard Walkthrough

The report has **11 pages**: one page per business question (Q7 to Q12), performance pages by product, customer and region, a schema-checking page, and the final **Executive Dashboard**.

**Executive Dashboard visuals**

- **KPI Cards**: Total Net Sales, Total Production Cost and Total Profit
- **Slicers**: Year and Quarter
- **Year Wise Sales** (column chart): sales growth by year
- **Sales Amount vs Production Cost** (combo chart): revenue against cost by year
- **Monthly Seasonality Trend** (line chart): sales pattern across the calendar year
- **Quarter Wise Sales** (pie chart): share of sales by quarter
- **Top 5 Products by Sales** (bar chart): best-selling products
- **Geographic Revenue Split** (bar chart): sales by territory

## 💡 Key Insights

- **Total sales: $29.36M** with a production cost of **$17.28M**, giving a profit of **$12.08M** and a **41.1% profit margin**.
- **2013 was the peak year** at **$16.35M**, more than double 2012. 2010 and 2014 contain only partial data.
- **Q4 is the strongest quarter** with about 31% of sales, and **December is the top month** at $3.21M.
- **Australia is the #1 region** with $9.06M (about 31% of sales), followed by the Southwest US and the Northwest US.
- **All top 5 products are Mountain-200 bikes**, together worth $6.67M (about 23% of sales).

## 📈 Business Impact

- **Sales planning:** prepare inventory and staffing for the Q4 peak.
- **Product strategy:** the Mountain-200 series is the revenue anchor, so protect its supply.
- **Regional focus:** Australia and the US West are the core markets, while the smaller US regions need a growth plan.

---

## 📁 Repository Files

- `POWER_BI_PROJECT_ADVENTURE_WORKS.pbix`: Power BI report file
- `dashboard.png`: dashboard preview

## 🧠 Skills Demonstrated

Power Query (ETL) • Data modeling (star schema) • DAX • Interactive dashboard design • KPI design • Business storytelling

## 📊 Dashboard Image




**🔗 Live Report:** [View on Power BI Service](YOUR_POWER_BI_LINK)

![Power BI Executive Dashboard]([YOUR_DASHBOARD_IMAGE_LINK](https://github.com/srs97023-rgb/Power-BI-Project/blob/main/PowerBI_Dashboard_image.jpg))

---
