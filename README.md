
# 🛒 Blinkit Grocery Analysis Dashboard

## Recommended Structure and Order

### 1. Project Title / Headline  
**🛒 Blinkit Grocery Insights: Outlet & Item Performance Dashboard**  
A real-time, interactive data visualization dashboard to analyze grocery item sales, outlet performance, fat content distribution, and customer behavior across different store types and regions.

---

### 2. Short Description / Purpose  
The Blinkit Dashboard is a visually intuitive Power BI report designed to monitor grocery retail data across outlets, items, and customer trends. It assists business teams in identifying high-performing outlets, managing inventory, and making region-specific decisions with confidence.

---

### 3. Tech Stack  
The dashboard was built using the following tools and technologies:<br>
• 📊 **Power BI Desktop** – Main platform for building and sharing the report.<br>
• 📂 **Power Query** – Data cleansing and transformation tool for raw grocery data.<br>
• 🧠 **DAX (Data Analysis Expressions)** – Used for KPIs, dynamic metrics, and conditional formatting.<br>
• 🧩 **Data Modeling** – Table relationships (outlet, item, sales, and ratings) enable cross-filtering.<br>
• 📁 **File Format** – `.pbit` for template sharing and `.xlsx` as the base data source.

---

### 4. Data Source  
**Source**: Simulated Blinkit sales and outlet dataset (Excel-based internal format).  

Data includes:  
- Item types, fat content, sales volume, and visibility  
- Outlet metadata (size, tier, location, type)  
- Ratings, establishment trends (2012–2022)  
- Average sales per item and outlet type

---

### 5. Features / Highlights

#### • Business Problem  
Blinkit manages a wide range of grocery SKUs across many outlet types and city tiers. However, identifying patterns in sales performance, outlet behavior, and product preferences was difficult due to scattered and unaggregated data.

Key questions addressed:
- Which tier or outlet type is most profitable?
- Which item categories contribute most to sales?
- How do fat content and ratings influence performance?

---

#### • Goal of the Dashboard  
To deliver a comprehensive, visual decision-making tool that:<br>
- Tracks item-level sales and outlet-level performance<br>
- Supports decisions related to marketing, expansion, and stocking<br>
- Compares outlets by location, size, and type<br>
- Helps identify top-performing categories and customer behavior

---

#### • Walkthrough of Key Visuals  

- **🔢 KPI Cards**  
  - **Total Sales**: `$1.20M`  
  - **Number of Items**: `8523`  
  - **Avg Sales**: `$141`  
  - **Avg Rating**: `4`

- **📈 Outlet Establishment (Line Graph)**  
  Sales and establishment growth over the years (2012–2022), peak in 2018 at $0.20M.

- **🍩 Outlet Size Distribution (Donut Chart)**  
  - Medium Outlets: `$444.79K`  
  - Small Outlets: `$248.99K`

- **📍 Outlet Location by Tier (Bar Chart)**  
  - Tier 3: `$472.13K`  
  - Tier 2: `$393.15K`  
  - Tier 1: `$336.40K`

- **🥛 Fat Content Analysis**  
  - Regular: `$776.32K`  
  - Low Fat: `$425.36K`  
  Shown via donut chart and tier-wise bar chart

- **📦 Item Type Analysis**  
  Top selling categories include:  
  - Fruits & Vegetables: `$0.18M`  
  - Snacks: `$0.18M`  
  - Household, Frozen, Dairy, etc.

- **📋 Outlet Type Comparison (Matrix Table)**  
  Compared on:  
  - Total Sales  
  - Item Count  
  - Average Rating  
  - Average Sales  
  - Item Visibility

---

#### • Business Impact & Insights  
- **Sales Optimization**: Identify top-performing outlets and item categories for promotions  
- **Customer Experience**: Track rating trends across outlet types and sizes  
- **Strategic Stocking**: Understand where and what to restock based on item-level sales  
- **Expansion Planning**: Tier 3 and Medium outlets show high revenue potential

---

### 6. Screenshots / Demos  
![Dashboard Preview](https://github.com/thrinesh01/Blinkit-dashboard/blob/main/Power%20BI%20Desktop%2025-07-2025%2022_21_33.png)
