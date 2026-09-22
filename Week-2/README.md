# 📊 Power BI Data Modeling, DAX, Sales Dashboard – Week 2

**📌 Project Overview**
This project focuses on building an **interactive sales analysis dashboard using Microsoft Power BI**. The Superstore sales dataset was transformed into a structured data model using dimension tables, relationships, DAX measures, and interactive visualizations.
The dashboard provides insights into **sales, profit, orders, quantity, profitability, category performance, regional performance, and sales trends**.

**🎯 Objectives**
* Build a structured **star schema** data model.
* Create dimension tables for customers, products, locations, and dates.
* Establish relationships between dimension and sales tables.
* Create reusable **DAX measures**.
* Develop KPI cards for important business metrics.
* Analyze sales performance by category and region.
* Visualize sales trends over time.
* Add interactive slicers and cross-filtering.
* Create tooltips and drill-down functionality.
* Build an interactive Power BI dashboard.

## 🗂️ Data Model
The project uses the following tables:
* `samplesuperstore` – Main sales/fact table
* `DimCustomer` – Customer information
* `DimProduct` – Product and category information
* `DimLocation` – Geographical information
* `DimDate` – Date and time-related information
* `_Measures` – Dedicated table for DAX measures
### Relationships
The dimension tables are connected to the `samplesuperstore` table using **one-to-many (1:*) relationships**.

**🧮 DAX Measures**

The following measures were created:

```DAX
Total Sales = SUM(samplesuperstore[Sales])
```

```DAX
Total Profit = SUM(samplesuperstore[Profit])
```

```DAX
Total Orders = DISTINCTCOUNT(samplesuperstore[Order ID])
```

```DAX
Total Quantity = SUM(samplesuperstore[Quantity])
```

```DAX
Average Sales = AVERAGE(samplesuperstore[Sales])
```

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

**📈 Dashboard Visualizations**
The dashboard includes:
* **Total Sales KPI**
* **Total Profit KPI**
* **Total Orders KPI**
* **Total Quantity KPI**
* **Profit Margin % KPI**
* **Category Performance Chart**
* **Regional Sales/Profitability Chart**
* **Sales Trend Line Chart**
* **Decomposition Tree**
* **Interactive Slicers**
* **Report Page Tooltip**
* **Cross-Filtering**
* **Drill-Down Analysis**

**🎛️ Interactive Features**
### Slicers
The dashboard provides slicers for:
* Year
* Region
* Category
* Segment
### Cross-Filtering
Selecting a data point in one visual dynamically filters related visuals and KPI cards.
### Tooltips
Hovering over visual elements displays additional information such as sales, profit, orders, and profit margin.
### Drill-Down
Hierarchical analysis is enabled through:
**Year → Quarter → Month**
and
**Category → Sub-Category → Product**

**🛠️ Tools Used**
* **Microsoft Power BI Desktop**
* **DAX**
* **Superstore Sales Dataset**

**📊 Key Skills Demonstrated**
* Data modeling
* Star schema design
* Dimension table creation
* Relationship management
* DAX calculations
* KPI development
* Data visualization
* Interactive dashboard design
* Drill-down analysis
* Cross-filtering
* Report page tooltips
* Time-based analysis

**📁 Project Structure**
Power-BI-Superstore-Sales-Analysis/
│
├── README.md
├── Power BI Report (.pbix)
├── Week 2 Documentation.pdf
└── Screenshots/

**🏁 Conclusion**
This project demonstrates how **Power BI and DAX** can be used to transform raw sales data into an interactive business intelligence dashboard. The structured data model, calculated measures, KPIs, and interactive visuals provide a comprehensive view of sales and profitability performance.
