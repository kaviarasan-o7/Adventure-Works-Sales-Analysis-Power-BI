# Adventure-Works-Sales-Analysis-Power-BI
This Project goal is to analyze sales performance, identify top-selling products, and track key performance indicators (KPIs) for the Adventure Works.

🔴 Live Interactive Dashboard
The best way to experience this project is through the live, interactive report.

➡️ View the Live Dashboard Here

(Note: You can get this link from the "File" -> "Publish to web (public)" option in the Power BI service.)

📊 Dashboard Preview
(Replace this placeholder with a high-quality screenshot of your main dashboard page)

🎯 Project Goal
This dashboard was created to provide the Adventure Works management team with a powerful tool to monitor business health. The goal is to move beyond static spreadsheets and enable dynamic, real-time analysis of sales and profitability KPIs.

📈 Key Questions Answered by the Dashboard
This dashboard helps business leaders answer critical questions such as:

How are our total sales and profit margins trending over time?

Which product categories and subcategories are the most and least profitable?

Which sales territories are top performers, and where are the opportunities for growth?

What are the sales figures for the current year compared to the previous year?

Who are our key customers and what are their purchasing patterns?

🛠️ Technical Details
Data Source: The project uses the official Microsoft Adventure Works sample dataset.

Data Modeling: A star schema was created in Power BI to connect the FactInternetSales table with dimension tables like DimProduct, DimCustomer, DimDate, and DimSalesTerritory.

Data Transformation: Power Query was used for data cleaning, merging columns (e.g., customer first and last names), and creating conditional columns for analysis.

Analytics: DAX (Data Analysis Expressions) was used to create all key measures and KPIs.

DAX Measure Highlight: Profit Margin %
Here is an example of a key DAX measure used to calculate the overall profit margin.

Profit Margin % =
VAR TotalRevenue = SUM(FactInternetSales[SalesAmount])
VAR TotalCost = SUM(FactInternetSales[TotalProductCost])
RETURN
    DIVIDE(
        TotalRevenue - TotalCost,
        TotalRevenue,
        0
    )
