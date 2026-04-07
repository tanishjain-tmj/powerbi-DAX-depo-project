# 📊 Power BI DAX Project – Sales & Returns Analysis

## 🧠 Project Overview

This project focuses on analyzing **Sales and Returns data** using Power BI.
The objective is to generate meaningful insights by applying DAX concepts such as calculated columns, measures, and time intelligence.

---

## 🎯 Objectives

* Analyze overall **sales performance**
* Evaluate **profitability**
* Track and analyze **product returns**
* Perform **time-based analysis (Year-over-Year and Month-over-Month)**
* Understand **filter context behavior**

---

## 📁 Dataset Tables

The project uses the following tables:

* Sales_Fact
* Returns_Fact
* Customer_Dim
* Product_Dim
* Date_Dim
* Region_Dim

---

## 🔗 Data Model

Relationships were established between fact and dimension tables to ensure proper data flow:

* Sales linked with Customer, Product, Date, and Region tables
* Returns linked with Sales table

All relationships follow a **Many-to-One structure with single direction filtering**.

---

## 🧮 Calculated Columns

The following calculated columns were created:

* **Profit Column** – to calculate profit per transaction
* **Return Flag** – to identify whether a sale was returned or not
* **Customer Full Name** – created by combining first and last names

---

## 📊 Measures

Several measures were created to perform aggregation and analysis:

* Total Sales
* Total Cost
* Total Profit
* Return Rate
* Average Sales per Transaction

---

## ⚡ Time Intelligence

Time-based analysis was performed using:

* Year-over-Year (YoY) comparison
* Month-over-Month (MoM) comparison
* Running totals and cumulative analysis

---

## 📂 Measure Management

A dedicated table named **"Measures"** was created to organize all measures in one place.
This improves readability and maintains a clean data model.

---

## 🔍 Filter Context & Behavior

Different DAX techniques were used to understand how filters affect calculations.
This includes comparing values with and without filters applied.

---

## 🧠 DAX Concepts Covered

The project demonstrates the use of:

* Aggregation functions
* Logical conditions
* Text functions
* Date and time functions
* Iterator functions
* Filter and context-based calculations

---

## 🔗 Relationships & Data Integration

The project uses relationship-based functions to fetch related data from dimension tables into fact tables, ensuring proper integration across datasets.

---

## ⏳ Time-Based Analysis

Advanced time intelligence techniques were used to:

* Compare performance across different time periods
* Track growth trends
* Analyze cumulative performance over time

---

## 🎯 Additional Scenarios

Additional analysis includes:

* Categorizing sales into different segments (Low, Medium, High)
* Performing advanced aggregations using iterative calculations

---

## 📊 Final Output

* All results are displayed using **Matrix Visual only**
* Data is grouped by:

  * Region
  * Month
  * Product Category
  * Customer Segment

❌ No charts or other visualizations were used
✔ Only Matrix visual is used as per project requirements

---

## ✅ Key Learnings

* Difference between **Calculated Columns and Measures**
* Importance of **data modeling and relationships**
* Understanding **filter context in DAX**
* Applying **time intelligence functions**
* Building a structured and optimized Power BI report

---

## 📌 Conclusion

This project demonstrates how Power BI can be used to build a complete analytical solution using DAX. It highlights practical implementation of business logic, data modeling, and time-based analysis for better decision-making.

---

## 📎 Dataset

Dataset was provided separately as part of the project.


---
