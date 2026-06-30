# Executive Business Performance Dashboard | Power BI

<img width="880" height="498" alt="image" src="https://github.com/user-attachments/assets/6f965a7c-4e5d-45a9-89e0-87f7201c2e07" />


## 📌 Overview

An interactive **Power BI Executive Business Performance Dashboard** built using a **star schema** data model to analyse business performance across **Sales, Customers, Products, Sales Team, and Forecasting**. The project demonstrates Power Query transformations, DAX measures, interactive filtering, Row-Level Security (RLS), forecasting, and business storytelling through executive-level dashboards.

---

## 📊 Project Highlights

- Designed a **5-page interactive executive dashboard**
- Built a **Star Schema** data model with Fact and Dimension tables
- Performed data cleaning and transformation using **Power Query**
- Created **14 business-focused DAX measures**
- Implemented **dynamic KPI indicators** displaying Month-over-Month growth/decline
- Implemented **Row-Level Security (RLS)** to enforce regional data access controls
- Included **15-day forecasting** for Revenue, Units Sold, and Order Volume
- Designed using a clean, corporate-style layout focused on executive decision-making

---

## 🗂 Data Model

### Fact Table
- Sales

### Dimension Tables
- Calendar
- Customers
- Products
- Sales Team

Relationships follow a **One-to-Many** Star Schema from dimension tables to the Sales fact table.

---

## 📈 Key Performance Indicators (KPIs)

- Total Revenue
- Total Profit
- Total Customers
- Total Orders
- Total Units Sold
- Revenue YTD
- Revenue MoM %
- Profit YTD
- Profit MoM %
- Profit Margin %
- Average Order Value
- Average Selling Price
- Average Profit per Order
- Average Discount %

---

# Dashboard Pages

## 1️⃣ Executive Overview

### Purpose

Provides a high-level snapshot of overall business performance for executives.

### Visuals

- KPI Cards
- Monthly Revenue Trend
- Revenue by Category
- Profit by Region
- Revenue by Customer Segment
- Top Products Table
- Region and Year Slicers

### Screenshot

<img width="880" height="498" alt="image" src="https://github.com/user-attachments/assets/6f965a7c-4e5d-45a9-89e0-87f7201c2e07" />

---

## 2️⃣ Sales Analysis

### Purpose

Analyses sales performance over time and across different locations and product categories.

### Visuals

- KPI Cards
- Monthly Revenue Trend
- Monthly Profit Trend
- Revenue by State
- Orders by Category
- Monthly Sales Summary Table
- Year & Category Slicers

### Screenshot

<img width="889" height="500" alt="image" src="https://github.com/user-attachments/assets/c71f359d-f681-46b6-9f8a-e4b8fca63a96" />


---

## 3️⃣ Customer & Product Analysis

### Purpose

Analyses customer segments, product performance, brand contribution, and purchasing behaviour.

### Visuals

- KPI Cards
- Monthly Revenue by Customer Segment
- Top Customers
- Top Brands
- Profit by Customer Tier
- Customer Performance Table
- Customer Segment Slicer

### Screenshot

<img width="884" height="497" alt="image" src="https://github.com/user-attachments/assets/3fca7e70-821c-435e-8fb9-e374b41a2895" />


---

## 4️⃣ Sales Team Performance

### Purpose

Evaluates sales team performance, departmental profitability, and geographic employee distribution.

### Visuals

- KPI Cards
- Sales Team Distribution Map
- Top Salespersons
- Department-wise Profit
- Salesperson Performance Table
- Territory Slicer

### Screenshot

<img width="879" height="499" alt="image" src="https://github.com/user-attachments/assets/b8223c03-072c-47a7-a4af-23bc8bd47597" />


---

## 5️⃣ Forecasting

### Purpose

Forecasts future business performance using Power BI's built-in forecasting capability.

### Visuals

- KPI Cards
- Revenue Forecast
- Unit Sales Forecast
- Order Volume Forecast

### Screenshot

<img width="877" height="499" alt="image" src="https://github.com/user-attachments/assets/6c1f5df9-8bd9-4394-96ac-e12cac7c1f6d" />


---

# Row-Level Security (RLS)

Implemented **Row-Level Security (RLS)** to simulate regional access control within Power BI Desktop.

### Roles

- East Manager
- West Manager
- North Manager
- South Manager

Each role can view data only for its assigned sales region using Power BI's **View As** functionality.

---

# Business Notes

- This project represents a **Business-to-Business (B2B)** sales environment.
- The **Customer_Name** field contains **company names** rather than individual customer names because each customer represents a business client.
- The dashboard is designed to support executive decision-making by providing clear KPIs, trends, operational insights, and forecasts.

---

# Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Data Modelling
- Row-Level Security (RLS)

---

# Skills Demonstrated

- Power BI Dashboard Development
- Data Modelling (Star Schema)
- Power Query (ETL)
- DAX
- KPI Design
- Row-Level Security (RLS)
- Forecasting
- Business Intelligence
- Data Visualization
- Executive Dashboard Design
- Sales Analytics
