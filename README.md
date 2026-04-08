# 📊 Customer Retention & Churn Analysis

---

## 📌 Project Overview

This project analyzes a **telecom customer dataset** to understand customer churn behavior and identify key factors affecting customer retention.

The objective is to simulate a **real-world business analytics scenario**, where customer data is cleaned, analyzed, and visualized to generate **actionable insights** for reducing churn and improving retention.

The final output is an **interactive Tableau dashboard** that highlights:

- Customer churn patterns  
- Retention trends over time  
- High-risk customer segments  
- Key drivers influencing churn  

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|--------|
| Python (Jupyter Notebook) | Data cleaning and preprocessing |
| Pandas | Data manipulation and feature engineering |
| Tableau Public | Data visualization and dashboard creation |
| GitHub | Project documentation and version control |

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset  

The dataset contains **7043 customers** with demographic, subscription, and billing information.

### Key Columns

| Column | Description |
|------|-------------|
| customerID | Unique customer identifier |
| tenure | Number of months customer stayed |
| Contract | Subscription type (Monthly, Yearly) |
| MonthlyCharges | Monthly subscription cost |
| TotalCharges | Total amount spent |
| PaymentMethod | Payment type used |
| Churn | Whether customer left (Yes/No) |

---

## 🧹 Data Cleaning & Preparation

Data preprocessing was performed using **Python (Pandas)**.

### Cleaning Steps

- Converted `TotalCharges` to numeric format  
- Handled missing values  
- Standardized categorical variables (Yes/No → 1/0)  
- Ensured data consistency for analysis  

---

## ⚙️ Feature Engineering

New features were created to enable deeper analysis:

- **Churn Flag:** Converted churn into numeric format (1 = churn, 0 = retained)  
- **Retention Flag:** Indicates active customers  
- **Tenure Groups:** Segmented customers based on lifecycle stages  
- **Charge Groups:** Categorized customers based on pricing tiers  
- **Customer Lifetime Value (CLV):**  
  `MonthlyCharges × tenure`  

---

## 📊 Dashboard Visualizations

The Tableau dashboard includes the following key visualizations:

---

### 1️⃣ Churn by Contract Type
📌 Shows how subscription type impacts churn  

![Churn Rate by Contract](images/Churn%20Rate%20By%20Contract.png)

---

### 2️⃣ Churn by Customer Tenure
📌 Identifies when customers are most likely to leave  

![Churn Rate by Tenure](images/Churn%20Rate%20By%20Tenure.png)

---

### 3️⃣ Churn by Monthly Charges
📌 Analyzes the impact of pricing on churn  

![Churn Rate by Charges Group](images/Churn%20Rate%20By%20Charge%20Group.png)

---

### 4️⃣ Churn by Payment Method
📌 Highlights friction points in billing experience  

![Churn by Payment](images/Churn%20Rate%20By%20Payment%20Method.png)

---

### 5️⃣ Customer Churn Trend (Cohort Analysis)
📌 Shows churn behavior across customer lifecycle  

![Cohort Trend](images/Churn%20Rate%20By%20Cohort.png)

---

## 📈 Key Insights

### 🔴 High Churn Drivers
- Customers with **month-to-month contracts** have the highest churn  
- Customers in their **first year** are most likely to leave  
- **Electronic check users** show significantly higher churn  

---

### 🟢 Low Churn Segments
- Customers with **long-term contracts** have very low churn  
- High tenure customers are more stable and loyal  

---

### ⚖️ Pricing Impact
- Pricing has **limited impact** compared to contract type and tenure  
- Churn is more influenced by **commitment and experience**  

---

## 💡 Business Recommendations

Based on the analysis, the following strategies are recommended:

- Encourage long-term subscriptions through discounts and offers  
- Improve customer onboarding experience (first 6–12 months critical)  
- Target high-risk users with retention campaigns  
- Optimize payment methods and billing experience  
- Monitor early churn signals and take proactive action  

---

## 📊 Tableau Dashboard

Explore the interactive dashboard:

🔗 https://public.tableau.com/app/profile/jerolin.mathew/viz/Future_DS_02/Dashboard1?publish=yes  

---

## 📁 Project Structure

```
Customer-Retention-Churn-Analysis
│
├── data
│   ├── telco_churn_original.csv
│   └── telco_churn_cleaned.csv
│
├── notebooks
│   └── churn_analysis.ipynb
│
├── images
│   ├── dashboard.png
│   ├── churn_contract.png
│   ├── churn_tenure.png
│   ├── churn_charges.png
│   ├── churn_payment.png
│   └── cohort_trend.png
│
└── README.md
```

---

## 🚀 Future Improvements

- Build predictive churn models using machine learning  
- Perform customer segmentation using clustering  
- Integrate real-time dashboard updates  
- Add customer behavior analytics  

---

## 📌 Conclusion

This project demonstrates a complete **customer analytics workflow**, including:

- Data cleaning and preprocessing  
- Feature engineering  
- Churn and retention analysis  
- Data visualization and storytelling  
- Business insight generation  

The insights derived from this analysis can help businesses **reduce churn, improve retention, and increase long-term revenue**.
