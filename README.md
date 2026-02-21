
# 📊 Business Insights 360 – Power BI Project  

🔗 **Live Dashboard:** [Click here](https://app.powerbi.com/view?r=eyJrIjoiMTdkODQxYmYtM2I4YS00ZDc1LWEzMzItMDljMTdlY2IzOTQ5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 🌟 Project Overview  
AtliQ Hardware has been growing rapidly and expanding into global markets. To keep up with competitors who already rely on advanced analytics, the company decided to leverage **Power BI** for making data-driven decisions.  

This project, part of the **Codebasics Bootcamp**, focuses on building an **interactive dashboard** that answers key stakeholder questions across:  
- Finance  
- Sales  
- Marketing  
- Supply Chain  
- Executive  

---

## 💻 Tech Stack  
- SQL  
- Power BI Desktop  
- Excel  
- DAX  
- DAX Studio  

---

## 🛠️ Power BI Features  
- Data cleaning and transformations with **Power Query**  
- **Snowflake data modeling** for efficient relationships  
- Creating **measures and KPIs** using DAX  
- **Dynamic titles** that respond to applied filters  
- **Conditional formatting** with icons and colors  
- **Bookmarks & navigation buttons** for smooth report flow  
- **Drill-through** and **tooltips** for detailed insights  
- **Date table creation** using M language  
- **KPI indicators** for quick performance checks  
- **Data validation techniques** to ensure accuracy  

---

## 🏢 Company Background  
AtliQ Hardware sells computers and accessories through three main channels:  
- 🏬 Retailers  
- 🛒 Direct Sales  
- 📦 Distributors  

Recently, the company faced losses from a poorly planned store expansion in the USA, which was based only on surveys and Excel analysis. This highlighted the urgent need for a dedicated analytics system to reduce guesswork and improve business decisions.  

## 📂 Dataset Details  

The project uses two databases provided in the Bootcamp: **gdb041** and **gdb056**.  
Together, they cover customers, products, markets, sales, forecasts, and associated costs.  

---

### 🗄️ gdb041  

- **dim_customer**  
  - 27 markets (e.g., India, USA, Spain)  
  - 75 unique customers  
  - Platforms: *Brick & Mortar* (offline), *E-commerce* (Amazon, Flipkart, etc.)  
  - Channels: Retailer, Direct, Distributor  

- **dim_market**  
  - Market details grouped into **7 sub-zones** and **4 regions** (APAC, EU, NAN, LATAM)  

- **dim_product**  
  - Divisions: P&A (Peripherals & Accessories), PC (Notebooks & Desktops), N&S (Networking & Storage)  
  - 14 product categories (e.g., Internal HDD, Keyboard) with multiple variants  

- **fact_forecast_monthly**  
  - Monthly demand forecasts by customer  
  - Used to compare forecast vs. actual sales for inventory planning  

- **fact_sales_monthly**  
  - Monthly actual sales quantities  
  - Helps track performance against forecast  

---

### 🗄️ gdb056  

- **freight_cost** – Logistics and freight expenses by market & fiscal year  
- **gross_price** – Gross product prices by product code  
- **manufacturing_cost** – Yearly manufacturing costs per product  
- **pre_invoice_deductions** – Trade discounts applied before invoicing (customer & year level)  
- **post_invoice_deductions** – Discounts and claims applied after invoicing  


## 💡 Dashboard Overview  

The dashboard provides a 360° view of AtliQ Hardware’s business operations across multiple domains:  

- ✅ **Home View** – Navigate seamlessly with a central landing page  
- ✅ **Finance View** – Analyze P&L statements, Net Sales trends, and top/bottom customers & products  
- ✅ **Sales View** – Explore customer and product performance with Net Sales, Gross Margin %, unit economics, and deductions  
- ✅ **Marketing View** – Gain insights by market, region, product, and customer, tracking GM% and NP% across segments  
- ✅ **Supply Chain View** – Track Forecast Accuracy, Net Error, and Absolute Error with trend analysis for optimization  
- ✅ **Executive View** – Monitor performance at a glance with revenue by division, customer, product, and channel  



## 🏠 Home Page
Central navigation hub with buttons to access each domain view.  

![Home Page](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0001.jpg)

---

## 💵 Finance View
Analyze Profit & Loss statements, Net Sales trends, and top/bottom customers & products.  

![Finance View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0002.jpg)

---

## 📈 Sales View
Customer and product performance with insights into Net Sales, Gross Margin %, and unit economics.  

![Sales View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0003.jpg)

---

## 📊 Marketing View
Market, region, product, and customer insights while tracking GM% and NP% across segments.  

![Marketing View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0004.jpg)

---

## 🚚 Supply Chain View
Track Forecast Accuracy, Net Error, and Absolute Error with trend analysis for supply chain optimization.  

![Supply Chain View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0005.jpg)

---

## 👔 Executive View
High-level performance overview including revenue by division, customers, products, and channels.  

![Executive View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0006.jpg)



## 🚀 Project Outcome  

This project demonstrates how **1.5M+ rows of raw data** were transformed into an **interactive, decision-focused dashboard**.  

It enables:  
- **Finance Teams** → Monitor profitability and sales performance  
- **Sales & Marketing Teams** → Identify key customers, products, and markets  
- **Supply Chain Teams** → Track forecast accuracy and optimize planning  
- **Executives** → Make smarter and faster decisions with confidence  
