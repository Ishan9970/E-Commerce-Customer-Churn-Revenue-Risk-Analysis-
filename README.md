# 📊 E-Commerce Customer Churn & Revenue Risk Analysis

## 📌 Project Overview
This project analyses customer churn behaviour in an e-commerce platform to identify key drivers of churn and estimate revenue impact.

The goal is to answer:
- Why customers churn
- Which segments are high-risk
- How churn affects revenue
- What actions can reduce churn

---

## 📂 Dataset
- Source: Kaggle (E-commerce Customer Churn Dataset)
- Total Records: 5,630 customers
- Features include:
  - Customer behaviour (tenure, app usage, orders)
  - Demographics (gender, city tier)
  - Transaction data (payment mode, order category)
  - Feedback signals (complaints, satisfaction)

---

## 🛠️ Tools Used

| Stage | Tool |
|------|------|
| Data Cleaning & Feature Engineering | Python (Pandas) |
| Data Analysis & KPI Extraction | SQL (MySQL) |
| Data Visualisation | Tableau |
| Summary Reporting | Excel |

---

## ⚙️ Key Steps Performed

### 1. Data Cleaning (Python)
- Handled missing values using median/mode
- Removed inconsistencies and ensured data quality
- Standardised categorical variables

### 2. Feature Engineering
- Created **ChurnFlag (1/0)**
- Built **Tenure Groups (0–6, 7–12, 13–24, 24+)**
- Developed **Engagement Score**
- Created **Revenue Proxy**
- Defined **Risk Segments**

---

### 3. SQL Analysis
- Calculated:
  - Overall churn rate
  - Revenue at risk
  - Segment-wise churn rates
- Identified high-risk customer groups and behavioural patterns

---

### 4. Tableau Dashboard
Developed an interactive dashboard including:

- KPI Cards:
  - Total Customers
  - Churn Rate
  - Revenue at Risk

- Visualisations:
  - Churn by Tenure
  - Churn by Payment Method
  - Churn by Product Category
  - Impact of Complaints on Churn

[📊 View Dashboard](https://public.tableau.com/views/E-CommerceCustomerChurnRevenueRiskAnalysisDashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📊 Key Insights

- **Overall Churn Rate:** 16.84% (~1 in 6 customers)
- **Revenue at Risk:** ~₹471K (14.7%)

### 🔥 Major Drivers

1. **New Customers (0–6 months)**
   - Churn Rate: **32.4%**
   - Indicates onboarding gaps

2. **Customer Complaints**
   - Churn Rate: **31.7% vs 10.9%**
   - Strongest predictor of churn

3. **Payment Method**
   - COD: **~25% churn**
   - Credit Card: **~13% churn**
   - Prepaid users show higher retention

4. **Product Category**
   - Mobile/Electronics: **~27% churn**
   - Grocery: **~4.9% churn**
   - Repeat-use categories retain better

---

## 💡 Business Recommendations

- Improve onboarding experience for new users
- Strengthen complaint resolution systems
- Promote prepaid payment incentives (UPI, cards)
- Increase engagement for low-activity customers
- Target high-risk segments with retention campaigns

---

## 🚀 Conclusion

This project demonstrates how data analytics can:
- Identify churn drivers
- Quantify revenue impact
- Support data-driven business decisions

---

## 👨‍💻 Author
Ishan Kukreti
