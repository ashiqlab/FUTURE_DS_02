# Customer Retention & Churn Analysis Dashboard

## Dashboard Preview
<img width="962" height="541" alt="image" src="https://github.com/user-attachments/assets/801cfbe9-377e-4341-8e99-58111e5aafec" />
Visual overview of the Power BI Dashboard showing customer retention, churn behavior, revenue trends, and subscription insights.

---

## 🧩 Project Overview

This Power BI project analyzes customer retention and churn patterns for a subscription-based business. The dashboard helps businesses understand why customers leave, identify high-risk customer segments, and improve long-term customer retention strategies.

The analysis focuses on churn trends by tenure, payment method, plan type, and gender while also tracking customer lifetime and revenue performance.

---

## 🎯 Objectives

* Analyze customer churn behavior and retention patterns.
* Identify which customer groups are most likely to churn.
* Measure churn rate, active customers, and customer lifetime value.
* Understand the impact of payment methods and subscription plans on churn.
* Provide actionable recommendations to improve retention and reduce churn.

---

## 🧹 Data Cleaning & Preparation

Performed in Power Query (Power BI):

* Removed duplicate customer records.
* Handled missing and inconsistent values.
* Standardized categorical fields such as payment methods and subscription plans.
* Converted data types for customer tenure, revenue, and churn status.
* Created grouped tenure categories for retention analysis.

---

## 📈 Key Metrics & DAX Measures

| Metric            | Formula / Description                                            |
| ----------------- | ---------------------------------------------------------------- |
| Total Customers   | Count of all customers                                           |
| Churned Customers | Customers marked as churned                                      |
| Active Customers  | Total Customers - Churned Customers                              |
| Churn Rate        | `Churn Rate = DIVIDE([Churned Customers], [Total Customers], 0)` |
| Average Lifetime  | Average tenure of customers                                      |
| Monthly Revenue   | Sum of monthly customer revenue                                  |

---

## 📊 Dashboard Features

### Customer Overview

* Displays total customers, active customers, churned customers, churn rate, and monthly revenue KPIs.

### Churn Analysis by Tenure

* Shows how churn changes based on customer subscription duration.
* Identifies that early-stage customers have the highest churn risk.

### Plan Type Distribution

* Visualizes customer distribution across subscription plans.
* Compares retention performance between monthly and long-term plans.

### Payment Method Analysis

* Highlights churn rate differences across payment methods.
* Helps identify payment-related churn behavior.

### Customer Lifetime Distribution

* Shows how customers are distributed across different tenure ranges.

### Demographic Analysis

* Compares churn behavior across gender categories.

### Insights & Recommendations Panel

* Provides business recommendations directly within the dashboard.

---

## 🧠 Insights Gained

* Early customer lifecycle stages showed the highest churn rates.
* Customers using electronic check payments had significantly higher churn.
* Long-term subscription plans demonstrated better customer stability.
* Gender had minimal impact on overall churn behavior.
* Retaining customers beyond the first year greatly improves customer lifetime value.

---

## 💡 Recommendations

* Promote long-term subscription plans with discounts or benefits.
* Improve onboarding experience during the first 90 days.
* Encourage customers to switch to more stable payment methods.
* Create targeted retention campaigns for high-risk customer groups.
* Monitor churn trends continuously using real-time dashboard updates.

---

## 🛠 Tools Used

* **Power BI** – Data visualization and dashboard creation
* **Power Query** – Data cleaning and transformation
* **DAX** – KPI calculations and business measures
* **Excel / CSV** – Data source management

---

## 👨‍💻 Author

**Ashiq Hussain**
