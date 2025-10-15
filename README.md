# 🛒 E-Commerce Sales Performance Dashboard  

## 📘 1. Background & Overview  

**NextCart Online Retailers** is a mid-sized e-commerce company specializing in **home goods, lifestyle accessories, and gift items**. With customers across more than 30 countries, the company processes thousands of online transactions every month through its online storefront.  

As the business scaled, the leadership team wanted deeper visibility into **sales performance, customer behavior, and profitability trends**. They faced challenges identifying which products and regions were most profitable, understanding seasonality in demand, and improving retention among one-time buyers.  

This project analyzes one year of NextCart’s sales data to answer key business questions such as:  
- Which products and countries generate the highest revenue?  
- What are the seasonal and monthly sales patterns?  
- Which customer segments demonstrate premium spending behavior?  
- How evenly distributed is revenue across the product catalog?  
- What opportunities exist to improve repeat purchases and retention?  

Using **Excel** for cleaning and initial exploration, **SQL** for analytical queries, and **Tableau** for visualization, this analysis transforms raw transactional data into actionable business insights.  

The final result — an **E-Commerce Performance Dashboard** — empowers stakeholders to track key KPIs, identify market opportunities, and make informed decisions about marketing, operations, and customer strategy.  

---

## 🧩 2. Data Structure Overview  

The dataset contains transactional-level details of online retail sales, including product information, order details, and customer demographics.  

| Column | Description |
|:--|:--|
| **InvoiceNo** | Unique order number identifying each transaction |
| **StockCode** | Product ID |
| **Description** | Product name |
| **Quantity** | Units sold per order |
| **InvoiceDate** | Date of purchase |
| **UnitPrice** | Price per unit |
| **CustomerID** | Unique customer identifier |
| **Country** | Customer’s country of purchase |

**Dataset Size:** ~50,000 rows  
**File Type:** CSV / Excel (~6 MB)  

📊 **Tools Used:**  
- **Excel:** Data cleaning, pivot tables, trend analysis  
- **MySQL:** Query-based analysis and aggregations  
- **Tableau:** Dashboard visualization and storytelling  

💡 *The dataset represents real-world retail behavior, allowing for exploration of profitability, product performance, and regional trends.*  

---

![Image Alt](https://github.com/zaher-insights/E-Commerce-Sales-Performance/blob/main/Total%20Sales%20by%20Country.png?raw=true)

![Image Alt](https://github.com/zaher-insights/E-Commerce-Sales-Performance/blob/main/Monthly%20Sales%20Tread.png?raw=true)

![Image Alt](https://github.com/zaher-insights/E-Commerce-Sales-Performance/blob/main/Average%20Order%20Value%20by%20Country.png?raw=true)

---

## 🧠 3. Executive Summary  

The analysis revealed that revenue is primarily driven by the **UK market**, with noticeable seasonal peaks in **December** due to holiday sales.  

While the **Top 10 products** generate consistent revenue, they make up only about **10% of total sales**, showing that performance is **evenly distributed** across a wide catalog.  

Additionally, customers from **the Netherlands** demonstrate higher **Average Order Values (AOV)**, signaling a premium segment.  

However, a significant number of customers appear to purchase only once — indicating strong acquisition but lower retention.  

---

## 📈 4. Insights Summary  

### 💰 **Revenue Distribution**
- The **Top 10 best-selling products** generated **$968,938.42**, representing roughly **10% of the total revenue ($10,245,768.75)**.  
- This suggests that while certain products perform well, overall sales are **well-distributed across the catalog** — with growth potential in mid-tier products.

### 🌍 **Regional Performance**
- The **United Kingdom** dominates overall revenue, accounting for the largest market share.  
- **Germany** and **France** follow as mid-tier regions, indicating potential for targeted regional expansion and marketing strategies.

### 📆 **Seasonality Trends**
- A strong **sales peak in December** reveals the influence of holiday shopping behavior.  
- This insight supports proactive **inventory planning** and **seasonal marketing campaigns**.

### 💎 **Average Order Value (AOV)**
- The **Netherlands** reports the **highest AOV**, highlighting a premium customer base.  
- Strategies like **exclusive offers, product bundles, or VIP programs** could capitalize on this market segment.

### 🔁 **Customer Retention Opportunity**
- Approximately **60% of customers** are **one-time buyers**, showing strong acquisition but limited repeat business.  
- **Loyalty programs, personalized recommendations, and re-engagement campaigns** can help increase customer lifetime value.

---

## 🧭 5. Recommendations  

✅ **Diversify product focus** — analyze and enhance mid-performing products to balance portfolio revenue.  
✅ **Double down on peak seasons** — plan inventory and promotions around the December sales surge.  
✅ **Grow high-value markets** — expand strategies in the Netherlands and Germany with localized promotions.  
✅ **Enhance customer loyalty** — implement retention tactics for one-time buyers to drive repeat purchases.  

---

## ⚙️ 6. Tools & Files  

| Tool | Purpose |
|------|----------|
| **Excel** | Data cleaning, pivot tables, charts |
| **MySQL** | Querying and aggregating transactional data |
| **Tableau** | Interactive dashboard creation |
| **GitHub** | Portfolio documentation |

📂 **Files in this Project**  
- `Ecommerce_Cleaned.xlsx` – [Cleaned dataset] (https://www.kaggle.com/datasets/vijayuv/onlineretail/data) 
- `Ecommerce_Queries.sql` – SQL queries for analysis  
- `Ecommerce_Dashboard.twbx` – [Tableau dashboard](https://public.tableau.com/app/profile/zaher.ahmed/viz/OnlineRetail_17604660812430/Dashboard2)  


---

## 🖥️ 7. Dashboard Preview  

**Tableau Dashboard Includes:**  
- 🌍 Sales by Country (Map)  
- 📦 Top 10 Products by Revenue (Bar Chart)  
- 📆 Monthly Sales Trend (Line Chart)  
- 💰 Average Order Value by Country (Bar Chart)  
- 👥 KPI Cards: Total Revenue | Total Orders 


---

## 🪶 8. Key Takeaways  

- The business has a **strong UK base** with scalable opportunities in other European markets.  
- Revenue is **diversified**, but mid-tier products can be optimized for greater growth.  
- Seasonal demand is clear — **December** is the golden month for sales.  
- Customer retention remains a key area for long-term revenue growth.  
