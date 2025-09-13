# Adventure-Works-Sales-Analysis-Power-BI
This Project goal is to analyze sales performance, identify top-selling products, and track key performance indicators (KPIs) for the Adventure Works.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Dataset](https://img.shields.io/badge/Dataset-AdventureWorks-blue?style=for-the-badge)

An interactive dashboard for the Adventure Works, designed to provide deep insights into sales performance, product profitability, and customer trends.

---

### 🔴 Live Interactive Dashboard
The best way to experience this project is through the live, interactive report.

**[➡️ View the Live Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiYOUR_PUBLIC_LINK_HEREIiwi...)**

*(Note: You can get this link from the "File" -> "Publish to web (public)" option in the Power BI service.)*

---

### 📊 Dashboard Preview

*(Replace this placeholder with a high-quality screenshot of your main dashboard page)*
![Dashboard Overview](https://placehold.co/800x450/2d3748/ffffff?text=Replace+with+Your+Dashboard+Screenshot)

---

### 🎯 Project Objective

The goal of this project is to provide the Adventure Works management team with a powerful tool for monitoring business health. The dashboard consolidates complex sales data into an easy-to-understand format, enabling stakeholders to move beyond static reports and make dynamic, data-driven decisions.

---

### 📈 Key Questions Answered by the Dashboard

This dashboard helps business leaders answer critical questions such as:
-   How are our total sales and profit margins trending over time?
-   Which product categories and subcategories are the most and least profitable?
-   Which sales territories are top performers, and where are the opportunities for growth?
-   What are the sales figures for the current year compared to the previous year (YoY Growth)?
-   Who are our key customers and what are their purchasing patterns?

---

### 🛠️ Technical Showcase

-   **Data Source:** The project uses the official **Microsoft Adventure Works** sample dataset, connecting to multiple tables to build a comprehensive view.
-   **Data Modeling:** A star schema was created in Power BI to form the analytical backbone of the report. This model connects the `FactInternetSales` table with key dimension tables like `DimProduct`, `DimCustomer`, `DimDate`, and `DimSalesTerritory`, ensuring optimal query performance and intuitive analysis.

    *(Replace this placeholder with a screenshot of your Data Model view)*
    ![Data Model](https://placehold.co/600x400/4A5568/ffffff?text=Data+Model+Screenshot)

-   **Data Transformation (Power Query):** Power Query was used extensively for data cleaning and preparation:
    -   Corrected data types for dates, currencies, and numerical IDs.
    -   Merged `FirstName` and `LastName` to create a `FullName` column for customers.
    -   Created conditional columns to segment data, such as categorizing 'Income Levels'.
    -   Removed unnecessary columns to optimize the data model's size and performance.

-   **DAX Measures:** Complex DAX measures were written to create the KPIs and power the visuals.

---

### 🚀 How to Use this File

1.  Download and install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
2.  Clone or download this repository.
3.  Open the `.pbix` file in Power BI Desktop to explore the full report, data model, queries, and DAX measures.
