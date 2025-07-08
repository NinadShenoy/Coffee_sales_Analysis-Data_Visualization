#  Coffee Sales Analysis – Power BI Project

## Table of Contents
- [Project Objective](#project-objective)
- [Dataset Overview](#dataset-overview)
- [Business Questions Answered](#business-questions-answered)
- [Power BI Report Features](#power-bi-report-features)
- [Tools & Technologies](#tools--technologies)
- [AI Assistance Used](#ai-assistance-used)
- [Project Workflow](#project-workflow)
- [Dashboard Previews](#-dashboard-previews)
- [Project Insight](#project-insight)
- [Final Conclusion](#final-conclusion)

---

##  Project Objective

This project simulates a coffee sales analysis for a fictional coffee selling outlet. It uses payment method, coffee type, time of the day to answer key business questions. The entire analysis is built in Power BI and focuses on Revenue, sales, customers behavior, payment and transaction insight

---

##  Dataset Overview

Payment method, Date & Time, Coffee Type, Cost Per Order

---

##  Business Questions Answered

1. **What is the Monthly revenue trend across different coffee products?**
2. **Which coffee products generate the most revenue, and during what times of day?**
3. **What percentage of transactions are card vs. cash, and how does that impact revenue?**
4. **Are there repeat card users indicating loyal customers?**
5. **What is the average spend per transaction, and how does it vary by coffee type or time of day?**
---


##  Power BI Report Features

###  KPIs

* Total Revenue
* Total Orders
* Avg Spend
* Total Card Payments

###  Trend Analysis

* Monthly revenue, Revenue by Time of Day
* Top products 

###  User Behavior 

* Payment mode impact
* Loyal customers by card ID

###  Comparative Analysis

* Coffee types by time
* Loyalty behavior via card usage

###  Interactive Filters

* Time range
* Coffee type
* Time of day
* Payment method

---

##  Tools & Technologies

* **Power BI Desktop** – for data modeling and dashboard creation
* **Excel** – used for mock data creation and basic cleaning
* **DAX (Data Analysis Expressions)** – for custom measures and calculations

  * Examples: `COUNT`, `CALCULATE`, `DIVIDE`, etc.

---

##  AI Assistance Used

I used **ChatGPT** to:

* Suggest the best visual types for presenting insights
* Structure the dashboard pages to tell a clear business story

---


##  Project Workflow

Below are the main steps followed to build this Power BI project:

1. **Data Cleaning**

   * Checked for missing values, errors, and duplicate entries.
   * Cleaned and transformed data using Excel and Power Query in Power BI.

2. **Data Preparation**

   * Assigned correct data types to each column (e.g., dates, numbers, text).
   * Created a **Time of The Day** custom column for marking parts of the day (used in comparative analysis).
   * Renamed columns for clarity and consistency.

3. **Dashboard Planning**

   * Created multiple report pages based on business questions:

     * Sales & Revenue
     * Customer & Payment Behavior
     * Transaction Insight

5. **Report Building**

   * Designed interactive visuals and KPIs.
   * Applied slicers and filters (Coffee Type, Payment Method, Date Range).
   * Used **DAX** for custom calculations like Total Revenue, Total Orders.

6. **Testing & Review**

   * Validated all visuals against source data.
   * Ensured performance and clarity for end users.

---

##  Dashboard Previews

### 1️ Executive Summary
![Executive Summary](https://raw.githubusercontent.com/NinadShenoy/Coffee_sales_Analysis-Data_Visualization/main/Screenshot-Executive%20Summary.png)

### 2️ Sales & Revenue
![Sales & Revenue](https://raw.githubusercontent.com/NinadShenoy/Coffee_sales_Analysis-Data_Visualization/main/Screenshot-Sales%20%26%20Revenue.png)

### 3️ Customer & Payment Behavior
![Customer & Payment Behavior](https://raw.githubusercontent.com/NinadShenoy/Coffee_sales_Analysis-Data_Visualization/main/Screenshot-Customer%20%26%20Payment%20Behavior.png)

### 4️ Transaction Insight
![Transaction Insight](https://raw.githubusercontent.com/NinadShenoy/Coffee_sales_Analysis-Data_Visualization/main/Screenshot-Transaction%20Insight.png)

---

### **Project Insight**

This coffee sales analysis shows the following key finding, 
* "₹115.43K revenue from over 3,600 orders was generated between Mar 2024–Mar 2025."
* "Latte is the top-selling drink across all months."
* "Noon-to-afternoon time slots generate the most revenue."
* "Cards are the dominant payment mode, accounting for 97.5% of transactions."
* "Loyal card users significantly contribute to recurring revenue and order volume."

---

###  **Final Conclusion**

The business has steady sales, loyal card-paying customers, and a consistent average spend. To grow more, it can run promotions during busy hours, upsell during quiet times, and offer rewards to frequent buyers. Future steps could include seasonal discounts, personalized offers, and keeping an eye on slow hours to improve menu or pricing.

---
