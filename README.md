# 📊Sales-Performance-Customer-Analytics-Dashboard


## 🧩 Project Overview
This project is an **interactive Sales Dashboard** built in **Power BI** to analyze sales performance, customer behavior, payments, product inventory, and employee performance.  
It provides a comprehensive view of business operations and helps decision-makers identify trends, opportunities, and KPIs to make data-driven decisions.

---

## 🎯 Objectives
- Analyze overall **sales performance** across customers, products, and time.
- Track **profitability** and identify top-performing products and sales representatives.
- Monitor **customer payments** and **credit utilization** for better financial insights.
- Evaluate **inventory levels** and product demand.
- Deliver actionable insights using **interactive visuals, filters, and DAX measures**.

---

## 🗂️ Dataset Description
The dashboard uses **8 interconnected tables**:

| Table | Description | Key Columns / Measures |
|-------|--------------|------------------------|
| **Customers** | Customer details and sales rep linkage | city, country, credit limit, customer number, salesRepEmployeeNumber, *customer_count* |
| **Employees** | Employee and sales rep information | full name, job title, office code, reportsTo |
| **Offices** | Office locations and contacts | city, country, office code, phone, state |
| **Order Details** | Individual order line information | buy price, quantity ordered, price each, profit, *total sales*, *most ordered products* |
| **Orders** | Order transactions | order number, order date, required date, shipped date, status, *total orders* |
| **Payments** | Customer payments | amount, cheque number, payment date |
| **Product Lines (Categories)** | Product categories | product line, description |
| **Products** | Product and inventory details | product code, product name, product line, quantity in stock, MSRP, stock requirement |

---

## ⚙️ Data Modeling
- Designed a **Star Schema** model connecting fact and dimension tables.
- Created **relationships** using primary and foreign keys (CustomerNumber, ProductCode, OrderNumber, OfficeCode).
- Built several **DAX measures** such as:
  - `Total Sales`
  - `Total Profit`
  - `Profit Margin`
  - `Pending Payment`
  - `Stock Turnover`
  - `Total Required Stock`
  - `Average Credit Limit`
  - `Customer Count`
  - `Purchase Cost`
  - `Total Orders`

---

## 📈 Dashboard Pages
1. **Executive Summary Dashboard** – Key KPIs: Total Sales, Total Profit, Total Orders, Purchase Cost, Profit Margin %.  
2. **Sales Performance** – Monthly Sales & Profit Trend, product, and sales rep performance.  
3. **Customers & Payments Insights** – Customer segmentation and payments.  
4. **Product & Inventory Analysis** – Product profitability and stock management insights.  
5. **Employees & Office Performance** – Comparison of regional and employee performance metrics.

---

## 🧰 Key Features
- Fully **interactive Power BI report** with slicers and filters.  
- **3 Tooltips** for contextual pop-up insights.  
- **2 Bookmarks** for quick navigation between report views.  
- Visually engaging **cards, charts, and KPIs**.  
- Built using **Power Query** for data transformation and **DAX** for calculations.

---

## 🖼️ Dashboard Preview

<img width="909" height="514" alt="Executive Summary Dashboard" src="https://github.com/user-attachments/assets/c68b56a9-495e-4a54-9328-1e76899b05c7" />
<img width="907" height="513" alt="Sales Performance" src="https://github.com/user-attachments/assets/09bef824-3748-4e9f-b125-4d18487bb86d" />
<img width="908" height="512" alt="Customer   Payment Insights" src="https://github.com/user-attachments/assets/3f0901e0-49a5-4258-9f65-a6ce7d74347f" />
<img width="906" height="510" alt="Product   Inventory Analysis" src="https://github.com/user-attachments/assets/d87af6e2-1e65-44f5-af27-b0def84d62ee" />
<img width="906" height="512" alt="Employees   Office Performance" src="https://github.com/user-attachments/assets/c240a261-af6f-4a58-9efd-7f48f8de916c" />

For a detailed view, download the full report PDF 👉 <a href= "https://github.com/Kashaf-naz/Sales-Performance-Customer-Analytics-Dashboard/raw/main/Sales%20Performance%20%26%20Customer%20Analytics%20Dashboard.pdf">Dashboard.pdf</a>

---

# 📁 Project File
Download and explore the full Power BI file:

👉 <a href= "https://github.com/Kashaf-naz/Sales-Performance-Customer-Analytics-Dashboard/raw/main/Sales%20Performance%20%26%20Customer%20Analytics%20Dashboard.pbix">Dashboard.pbix</a>
*(Open in **Power BI Desktop** to explore data modeling, DAX formulas, and interactive visuals.)*

---

## 🧠 Insights & Learnings
- Enhanced understanding of **data modeling** and **relationship building** in Power BI.  
- Improved proficiency with **DAX calculations** and **KPI design**.  
- Developed strong **data visualization and storytelling** skills.  
- Demonstrated ability to transform raw data into **strategic business insights**.

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **CSV (Data Source)**
- **Data Modeling (Star Schema)**

---

## 👩‍💻 Author
**Kashaf Naz**  
- 📧 kashafnaz225@gmail.com 
- 💼 www.linkedin.com/in/kashaf-naz


---

⭐ *If you find this project useful, consider giving it a star on GitHub!*
