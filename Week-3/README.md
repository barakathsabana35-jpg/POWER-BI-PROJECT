**Power BI Week 3 – Financial Data Analysis**

**📊 Project Overview**
This project focuses on analyzing Shopify stock market data using Microsoft Power BI. The report demonstrates data import, date dimension creation, data modeling, time-based analysis, and financial data visualization.

**🎯 Objectives**
Import and prepare stock market data in Power BI.
Create a dedicated Date Dimension table.
Establish relationships between the Date table and stock data.
Create a Year–Quarter–Month–Day date hierarchy.
Apply DAX time-intelligence functions.
Analyze stock closing price, trading volume, and daily returns.
Create interactive visualizations for financial analysis.

**🛠️ Tools Used**
Microsoft Power BI Desktop
Power Query
DAX
GitHub

**📌 Key Tasks Completed**
Data Import Shopify stock market data was imported into Power BI using Power Query for financial analysis.
Date Dimension A dedicated Dim_Date table was created with Date, Day, Month, Quarter, and Year fields.
Date Table The Dim_Date table was marked as the official Date Table to support accurate time-intelligence calculations.
Date Hierarchy A Year → Quarter → Month → Day hierarchy was created to enable drill-down analysis.
Data Modeling An active one-to-many relationship was established between the Date Dimension and the stock data table.
Stock Price Analysis A line chart was created to visualize stock closing price movements over time.
Time Intelligence The following DAX measures were created:
Close Price LY
Close Price Previous Year
Close Price YTD
Trading Volume YTD
These measures support year-over-year and year-to-date financial analysis.
Trading Volume & Daily Return A combination chart was created to analyze trading volume and daily return percentage over time.

**📈 Key Analysis**
The Power BI report provides a visual understanding of stock price movements, trading activity, and daily performance across different time periods. Time-intelligence measures allow financial values to be compared across previous-year and year-to-date periods.

**📂 Project Files**
PowerBI_Week3_Financial_Analysis.pbix – Power BI Desktop project
Week3_Report.pdf – Project documentation and screenshots
README.md – Project overview and documentation

**✅ Conclusion**
This project demonstrates the use of Power BI for financial data analysis. It covers data preparation, date modeling, relationships, DAX time-intelligence calculations, and interactive visualizations to analyze stock market performance.
