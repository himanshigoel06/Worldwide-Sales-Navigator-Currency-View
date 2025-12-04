# 🌍 Worldwide Sales Navigator – Currency View  

A dynamic, interactive Power BI dashboard that analyses worldwide internet sales across regions, currencies, and time—featuring user-driven filters, multi-currency conversion, and time-intelligence metrics to compare recent performance against historical trends.

---

## 📝 Short Description / Purpose  


The **Global Currency Pulse Dashboard** is an interactive Power BI report that helps users analyze internet sales across countries, time periods, and currencies by combining dynamic filters, time-intelligence measures, and multi-currency conversion.

It gives business stakeholders, analysts, and decision-makers a **real-time view** of worldwide sales performance in both base and selected currencies—enabling quick comparison of regions, trends, and customer segments.

---

## ⚙️ Tech Stack  

The dashboard was built using:

- **Power BI Desktop** – For report creation  
- **Power Query** – Data cleaning, shaping, and importing 5 tables  
- **DAX** – Dynamic currency measures, time-intelligence (1/3/6 months), titles  
- **Data Modeling** – Star schema with fact_InternetSales and dimension tables  
- **Bookmarks & Buttons** – For dropdown menus (Users, Currency, Sales Territory)  
- **File Formats**  
  - `.pbix` – Report development  
  - `.png` – Snapshot images  

---

## 📂 Data Source  

Dataset: **Worldwide Sales Navigator (Excel)**  
Includes:

- **fact_InternetSales** – Transaction-level sales (amount, currency, ship date, territory)  
- **dim_Customer** – Customer profiles  
- **dim_Date** – Supports time-series calculations  
- **SalesTerritory** – Country & region mapping  

Supports advanced regional analysis, currency variation impact, and customer insights.

---

## ⭐ Features / Highlights  

### 📌 **Business Problem**  
Global sales teams work with multiple currencies, customer types, and regions.  
But raw transaction data makes it hard to see:

- Which regions generate most revenue  
- Impact of currency fluctuations  
- Trending territories (1/3/6 months)  
- User-level sales performance  

Decision-makers need an intuitive way to compare performance across markets.

---

### 🎯 **Goal of the Dashboard**  
To create **a single, interactive global sales monitoring tool** that:

- Compares sales across countries, currencies, and users  
- Highlights market performance trends  
- Supports currency-based decision making  
- Identifies strong and weak regions  
- Provides quick insights through KPIs and dynamic visuals  

---

## 🖼️ Walkthrough of Key Visuals  

### ⭐ **KPI Cards**  
Shows:
- Total sales (selected currency)  
- Last month sales  
- All-time sales  

### 🎛 **Dynamic Title & Header**  
- Shows selected currency  
- Displays execution timestamp  
- Includes dropdown buttons (Users, Currency, Territory)

### 📈 **Monthly Sales Trend**  
- Stacked bars = All currency sales  
- Highlighted dot = Selected currency  
- Compare local vs global performance  

### 🗺️ **Map: Country-wise Product Sales**  
- Identifies high-demand regions  
- Displays total products sold per country  

### 📊 **Territory Performance Table**  
Includes:
- Total sales  
- Share of global revenue  
- 1/3/6 month trend  
- Conditional formatting highlights performance  

---

## 📊 Business Impact & Insights  

### 📌 Strategic Market Focus  
Highlights best-performing regions and underperforming markets.

### 📌 Revenue & Risk Visibility  
Shows how currency selection affects reported revenue, supporting financial decisions.

### 📌 Operational Efficiency  
Reduces manual reporting and speeds up monthly sales reviews.

---

## 🖼️ Screenshots / Demo  
| Dashboard Preview |  
|------------------|  
| ![Dashboard Preview](https://github.com/himanshigoel06/Worldwide-Sales-Navigator-Currency-View/blob/main/Multi-currency-sales-report-snapshot.png.png) |

---

## 🤝 Contributing  
Feel free to submit issues or pull requests for improvements.

---

## 📬 Contact  
**Himanshi Goel**  
📧 Email: **himanshigoel41@gmail.com**  
🔗 LinkedIn: **https://www.linkedin.com/in/himanshigoel06**
