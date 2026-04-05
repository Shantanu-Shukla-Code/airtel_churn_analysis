# 📊 Airtel Customer Churn Analysis Dashboard

## 📌 Overview

This project presents a **Customer Churn Analysis Dashboard** built using **Power BI**, inspired by the telecom industry and themed around **Airtel**.

The goal of this project is to analyze customer behavior, identify **key churn drivers**, and highlight **at-risk customer segments** to support data-driven retention strategies.

---

## 🎯 Objectives

* Understand overall **customer churn trends**
* Identify **factors contributing to churn**
* Analyze **service usage and its impact on churn**
* Explore **demographic influences on churn**
* Provide insights for **customer retention strategies**

---

## 📂 Dataset

The dataset used is a **Telco Customer Churn dataset**, which includes:

* Customer demographics (Gender, Senior Citizen, Partner, Dependents)
* Account information (Tenure, Contract, Payment Method)
* Services subscribed (Tech Support, Online Security, Streaming, etc.)
* Charges (Monthly & Total)
* Churn status (Yes/No)

---

## 🧱 Data Modeling

A **star schema approach** was used:

* **Fact Table**

  * CustomerID
  * Tenure
  * Monthly Charges
  * Total Charges
  * Churn

* **Derived Tables**

  * Service data (unpivoted for analysis)
  * Demographic attributes (unpivoted for comparison)

This structure improves **performance, scalability, and clarity** in Power BI.

---

## 📊 Dashboard Features

**Churn Overview**

Provides a high-level summary of churn behavior.

**Key KPIs**

* Total Customers
* Churned Customers
* Churn Rate
* Average Monthly Charges
* Average Tenure

**Visuals**

* Churn Rate by Internet Service Type
* Churn Rate by Service Type
* Churn by Payment Method
* Churn by Contract Type
* Churn by Gender
* Churn by Demographics

---

## 📈 Key Insights

* 📉 **Month-to-month contracts** show the highest churn rates
* 💸 Customers with **smaller tenure periods** tend to churn more
* 🛠️ Lack of **value-added services** (e.g., Tech Support, Online Security) is linked to higher churn
* 👴 **Senior citizens** have significantly higher churn rates
* 💳 **Electronic payment methods** are associated with increased churn

---

## 🎨 Design Approach

The dashboard is themed using **Airtel’s brand colors**: Red, Dark Grey & White

This ensures **visual clarity and brand consistency**.

---

## 🛠️ Tools & Technologies

* **Power BI** – Data visualization and dashboard creation
* **Power Query** – Data transformation (including unpivoting)
* **DAX** – Measures and calculated columns

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter by:

   * Contract Type
   * Internet Service
   * Payment Method
   * Demographics
3. Explore visuals to identify churn patterns

---

## 📌 Future Improvements

* Add **predictive churn modeling (ML integration)**
* Include **customer segmentation**
* Build a **risk scoring page**
* Enhance interactivity with drill-through analysis

---

## 📎 Conclusion

This dashboard demonstrates how data can be used to:

* Understand customer behavior
* Identify churn risks
* Support strategic decision-making

It reflects a **real-world telecom analytics scenario** and showcases practical **data modeling, DAX, and visualization skills**.

---
Shantanu Shukla
(Data Analyst | Power BI Enthusiast)
