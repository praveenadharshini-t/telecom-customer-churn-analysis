# Customer Churn Analysis – Identifying High-Risk Segments and Retention Strategies

## 📌 Problem Statement
Customer churn is a critical problem for telecom companies, leading to revenue loss and increased acquisition costs.
This project aims to identify key factors driving churn, uncover high-risk customer segments, and recommend data-driven strategies to improve retention.

---

## 📊 Dataset Overview

* Telecom customer dataset containing ~38 features
* Includes:

  * Customer demographics
  * Service usage (Internet, Phone, Add-ons)
  * Billing information (Monthly Charges, Offers)
  * Customer lifecycle (Tenure, Status)

---

## 🎯 Key Questions

* When do customers churn?
* Which customer segments have the highest churn?
* Does pricing influence churn behavior?
* How do service types impact churn?
* What is the most critical high-risk customer segment?

---

## 🔍 Analysis Approach

* Performed data cleaning and handled missing values appropriately
* Removed data leakage columns (Churn Reason, Churn Category)
* Created a binary churn flag for analysis
* Conducted segmentation analysis based on:

  * Tenure (customer lifecycle)
  * Contract type
  * Internet service type
* Combined multiple factors to identify high-risk customer groups

---

## 💡 Key Insights

### 🔴 Early Lifecycle Churn

* Customers in the **0–6 month tenure group** exhibit the highest churn
* Indicates that the **initial onboarding phase is a critical drop-off point**

---

### 🔴 Contract Type Impact

* **Month-to-month customers have significantly higher churn rates** compared to yearly contracts
* Lack of long-term commitment increases churn risk

---

### 🔴 Fiber Optic Risk Segment

* Fiber Optic users show **~41% churn rate**, highest among all service types
* Also have the **highest average monthly charges (~90)**
* Suggests a mismatch between **price and perceived value**

---

### 🔴 High-Risk Segment (Core Finding)

* Customers with:

  * **Fiber Optic service**
  * **Month-to-month contracts**
* Represent:

  * **~27% of total customers**
  * **~160K in monthly revenue**
* Exhibit **~59% churn rate**
* Majority of churn occurs within the **first 0–6 months**

---

## 🚀 Business Recommendations

* 🎯 **Convert high-risk users to long-term contracts**

  * Provide incentives such as discounted annual plans

* 📉 **Improve onboarding experience**

  * Focus on the first 3 months to reduce early churn

* 📢 **Targeted retention campaigns**

  * Proactively engage high-risk customers before churn

* 💰 **Re-evaluate pricing strategy for Fiber plans**

  * Ensure perceived value aligns with premium pricing

---

## 📈 Business Impact

Identified a high-risk customer segment contributing **~27% of total customers and ~160K in revenue**, enabling targeted strategies to reduce churn and improve customer lifetime value.

---

## 🛠️ Tools Used

* Python (Pandas, Matplotlib, Seaborn)
* Jupyter Notebook

---
