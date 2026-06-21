# 📊 Telecom Customer Churn Analysis

## Project Overview

Customer churn is a major challenge in the telecom industry, as losing customers directly impacts revenue and increases acquisition costs. This project analyzes telecom customer data to identify the key factors influencing churn and provide actionable business recommendations to improve customer retention.

**Dataset Size:** 7,043 Customers
**Churn Rate:** 26.54%

---

## Business Objective

The objective of this analysis is to:

* Identify customer segments with high churn risk.
* Understand the relationship between customer behavior and churn.
* Discover factors that improve customer retention.
* Generate data-driven recommendations for reducing churn.

---


## Key Findings

### 1. New Customers Are More Likely to Churn

Customers in their first few months of service show the highest churn rates. Churn is heavily concentrated among customers with very low tenure.

### 2. Contract Type Strongly Influences Churn

Month-to-month customers are significantly more likely to leave compared to customers with one-year or two-year contracts.

### 3. Senior Citizens Have Higher Churn Risk

Senior citizens churn at a higher rate than non-senior customers, making them an important segment for targeted retention efforts.

### 4. Value-Added Services Improve Retention

Customers subscribed to the following services are less likely to churn:

* Online Security
* Online Backup
* Tech Support
* Device Protection

### 5. Payment Method Impacts Churn

Customers using **Electronic Check** as their payment method exhibit the highest churn rate among all payment options.

### 6. Gender Has Minimal Impact

No significant difference was observed in churn behavior between male and female customers.

---

## High-Risk Customer Profile

Customers are most likely to churn when they have multiple characteristics below:

* Month-to-month contract
* Tenure less than 6 months
* Electronic Check payment method
* Senior citizen status
* No Online Security
* No Online Backup
* No Tech Support
* No Device Protection

---

## Visualizations

The analysis includes visualizations such as:

* Customer Churn Distribution
* Tenure vs Churn Analysis
* Contract Type vs Churn
* Payment Method vs Churn
* Senior Citizen Churn Analysis
* Service Adoption vs Churn


---

## Business Recommendations

### Improve Early Customer Experience

Implement a structured 90-day onboarding program to reduce churn among newly acquired customers.

### Promote Long-Term Contracts

Offer incentives and discounts to encourage customers to move from month-to-month plans to annual contracts.

### Increase Adoption of Value-Added Services

Bundle security, backup, and support services with telecom plans to increase customer engagement and retention.

### Optimize Payment Methods

Encourage Electronic Check users to switch to Auto-Pay or recurring digital payment methods.

### Support Senior Citizen Customers

Provide simplified plans, proactive support, and dedicated assistance programs for senior customers.

---

## Dataset Information

The dataset contains customer demographic information, account details, subscribed services, and payment-related attributes.

### Key Features

* Gender
* Senior Citizen
* Partner & Dependents
* Tenure
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Internet Services
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming Services
* Churn Status

### Data Cleaning

* Replaced missing values in `TotalCharges` for customers with zero tenure.
* Converted `TotalCharges` from object to numeric datatype.
* Verified no duplicate records.
* Performed exploratory data analysis (EDA) to identify churn patterns.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── TelecomChurnAnalysis.ipynb
├── telecom_customer_churn.csv
├── README.md

```

---

## Conclusion

The analysis revealed that customer churn is primarily driven by short tenure, month-to-month contracts, Electronic Check payments, lack of value-added services, and senior citizen status. By focusing on these factors, telecom companies can improve customer retention, reduce revenue loss, and increase customer lifetime value.

---

## Author

**Bhumika Maji**

Data Analytics Enthusiast
