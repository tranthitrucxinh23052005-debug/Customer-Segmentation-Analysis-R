# Sales Management System – SQL Project

## 📌 Project Overview
This project is a **Sales Management System** built with SQL Server, designed to manage customers, employees, products, invoices, and perform business analysis. It aims to provide actionable insights for business decision-making by analyzing sales data, customer behavior, and revenue trends.

---

## 🛠 Tech Stack
- SQL Server  
- T-SQL (Transactional SQL)  
- Database Design (Normalization – 3NF)  

---

## 📊 Database Schema
The database contains the following tables:

| Table Name | Description |
|------------|-------------|
| KHACHHANG | Customer information |
| NHANVIEN  | Employee and sales staff data |
| SANPHAM   | Product catalog |
| HOADON    | Invoice header |
| CTHD      | Invoice details |

**Relationships:**
- Primary Keys and Foreign Keys enforced  
- Normalized to **3NF** to ensure data consistency and avoid redundancy

---

## 🔍 Key Business Queries & Insights
1. **Product Filtering**
   - Filter products by category, price, or origin  
   - **Insight:** Identify most popular products within specific price ranges

2. **Sales Analysis**
   - Analyze invoices by date, employee, or customer  
   - **Insight:** Detect peak sales periods and top-performing employees

3. **Revenue Reports**
   - Aggregate revenue per product, per customer, and per period  
   - **Insight:** Highlight high-value transactions and profitable product categories

4. **Customer Segmentation**
   - Group customers by purchase behavior  
   - **Insight:** Target marketing efforts to high-value segments

---

## 📈 Example Outputs
*(Add screenshots or sample query results here)*  

Example:  # Sales Management System – SQL Project

## 📌 Project Overview
This project is a **Sales Management System** built with SQL Server, designed to manage customers, employees, products, invoices, and perform business analysis. It aims to provide actionable insights for business decision-making by analyzing sales data, customer behavior, and revenue trends.

---

## 🛠 Tech Stack
- SQL Server  
- T-SQL (Transactional SQL)  
- Database Design (Normalization – 3NF)  

---

## 📊 Database Schema
The database contains the following tables:

| Table Name | Description |
|------------|-------------|
| KHACHHANG | Customer information |
| NHANVIEN  | Employee and sales staff data |
| SANPHAM   | Product catalog |
| HOADON    | Invoice header |
| CTHD      | Invoice details |

**Relationships:**
- Primary Keys and Foreign Keys enforced  
- Normalized to **3NF** to ensure data consistency and avoid redundancy

---

## 🔍 Key Business Queries & Insights
1. **Product Filtering**
   - Filter products by category, price, or origin  
   - **Insight:** Identify most popular products within specific price ranges

2. **Sales Analysis**
   - Analyze invoices by date, employee, or customer  
   - **Insight:** Detect peak sales periods and top-performing employees

3. **Revenue Reports**
   - Aggregate revenue per product, per customer, and per period  
   - **Insight:** Highlight high-value transactions and profitable product categories

4. **Customer Segmentation**
   - Group customers by purchase behavior  
   - **Insight:** Target marketing efforts to high-value segments

---

## 📈 Example:  
SELECT TOP 5 ProductName, SUM(Quantity*Price) AS Revenue
FROM CTHD
JOIN SANPHAM ON CTHD.ProductID = SANPHAM.ProductID
GROUP BY ProductName
ORDER BY Revenue DESC;
## 📌 How to Run
1. Open `CSDL_KT_D04.sql` in SQL Server Management Studio  
2. Execute the script to create database and tables  
3. Run queries in SQL Server to generate reports and insights  

---

## 📈 Project Outcome
- Designed a fully normalized sales database (3NF)  
- Built analytical queries for product, sales, and revenue analysis  
- Extracted actionable insights to support business decision-making  
- Gained experience in database design, SQL queries, and data-driven business analysis  

---

## 🔗 Portfolio & Contact
**Author:** Tran Thi Truc Xinh  
**LinkedIn:** [https://www.linkedin.com/in/tranthitrucxinh](https://www.linkedin.com/in/tranthitrucxinh)  
**GitHub:** [https://github.com/tranthitrucxinh23052005-debug](https://github.com/tranthitrucxinh23052005-debug)  
**Email:** tranthitrucxinh23052005@gmail.com
