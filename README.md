# UK Delivery Operations – Data Analysis Project

## 📌 Project Overview
This project is a **client-ready data analysis solution** designed for a UK-based delivery and house-shifting company operating nationwide.  
It focuses on **accurate data collection, strong data validation, and analytics readiness**, built using Microsoft Excel and designed to scale into **Power BI dashboards**.

The system ensures clean, consistent, and reliable operational and financial data for business decision-making.

---

## 🎯 Business Objectives
- Standardize daily delivery data entry
- Track revenue, costs, and profitability
- Prevent data entry errors using validations
- Enable KPI reporting and trend analysis
- Prepare structured data for Power BI dashboards

---

## 🏗 Project Structure (Excel Sheets)

### 1️⃣ Master_Lists
Reference sheet containing controlled lists used for dropdown validations:
- Service Types
- Vehicle Types
- Fuel Types
- Load Types
- Delivery Status
- Cities (UK)

✅ Ensures data consistency across all sheets

---

### 2️⃣ Daily_Deliveries
Operational sheet capturing day-to-day delivery data.

**Key Fields:**
- Order ID
- Delivery Date
- City
- Service Type
- Vehicle Type
- Fuel Type
- Load Type
- Distance (km)
- Delivery Time (hours)
- Delivery Status

**Validations Applied:**
- Dropdown lists from Master_Lists
- Distance ≥ 0
- Delivery Time between 0.5 and 24 hours

---

### 3️⃣ Revenue_Details
Tracks income generated per delivery.

**Includes:**
- Base Charge
- Distance Charge
- Load Charge
- Discount
- Gross Revenue (calculated)
- Net Revenue (calculated)

**Formula Logic:**
***Net Revenue = Gross Revenue – Discount***

---

### 4️⃣ Cost_Details
Tracks operational expenses per delivery.

**Includes:**
- Fuel Cost
- Driver Wage
- Helper Wage
- Maintenance Cost
- Toll & Parking
- Other Costs
- Total Cost (calculated)

**Formula Logic:**
***Total Cost = Sum of all cost components***

---

## 🔐 Data Validation & Quality Controls
- Dropdown-only selections for categorical data
- Numeric fields restricted to non-negative values
- Error alerts to prevent invalid entries
- Formula cells protected from manual editing

---

## 📊 Analytics Readiness
The dataset is:
- ✔ Clean & validated
- ✔ KPI-ready
- ✔ Pivot-table friendly
- ✔ Fully compatible with Power BI

---

## 🚀 Future Enhancements
- KPI Summary Dashboard
- Pivot Tables & Charts
- Profitability Analysis
- Power BI Executive Dashboard

---

## 🧑‍💼 Ideal For
- Data Analyst Portfolios
- Client Delivery & Logistics Projects
- Internship / Entry-Level Analyst Demonstrations
- Power BI Dashboard Foundations

---

## 📎 Tools Used
- Microsoft Excel
- Data Validation
- Excel Formulas
- Analytics-ready data modeling

---

## 📬 Contact
If you’d like to collaborate or discuss this project, feel free to connect.

---
