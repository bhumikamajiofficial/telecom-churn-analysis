# 📊 Telecom Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

Customer churn is one of the most critical business challenges in the telecommunications industry. Acquiring a new customer often costs significantly more than retaining an existing one.

This project analyzes customer churn behavior using a telecom customer dataset containing information about customer demographics, account details, subscribed services, and payment behavior. The objective is to identify the key factors influencing churn and provide actionable business recommendations that can help improve customer retention and revenue stability.

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn within a Jupyter Notebook environment.

---

## 🎯 Business Objective

The primary goals of this analysis are:

* Identify the major drivers of customer churn.
* Understand customer segments most likely to leave.
* Discover retention opportunities.
* Provide data-driven recommendations to reduce churn.
* Support business decision-making through visual analytics.

---

## 📂 Dataset Description

### Dataset Information

| Attribute          | Value  |
| ------------------ | ------ |
| Total Customers    | 7,043  |
| Records            | 7,043  |
| Target Variable    | Churn  |
| Churned Customers  | 26.54% |
| Retained Customers | 73.46% |

### Features Included

The dataset contains customer information across multiple categories:

#### Customer Demographics

* Gender
* Senior Citizen Status
* Partner
* Dependents

#### Account Information

* Tenure
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges

#### Telecom Services

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

### Data Cleaning Performed

* Replaced missing `TotalCharges` values with 0 for customers having tenure = 0.
* Converted `TotalCharges` from object datatype to numeric.
* Removed data inconsistencies.
* Verified absence of duplicate records.
* Verified absence of missing values after preprocessing.

---

## 📈 Key Business Metrics

### Customer Distribution

| Metric             | Value  |
| ------------------ | ------ |
| Total Customers    | 7,043  |
| Retained Customers | 73.46% |
| Churned Customers  | 26.54% |

### Business Insight

Approximately **1 out of every 4 customers leaves the company**, indicating a significant opportunity for improving retention and protecting recurring revenue.

---

## 🔍 Exploratory Data Analysis Highlights

### 1. New Customers Churn the Most

**Observation**

* Highest churn occurs within the first few months of service.
* Customers with 1–2 months tenure exhibit the highest churn rates.
* Long-tenure customers demonstrate significantly stronger retention.

**Business Interpretation**

* Early customer experience strongly influences retention.
* The onboarding phase is the most critical period in the customer lifecycle.

---

### 2. Contract Type is the Strongest Churn Indicator

**Observation**

* Month-to-month contracts show the highest churn rates.
* One-year and two-year contract customers are significantly more loyal.

**Business Interpretation**

* Customers without long-term commitments can easily switch providers.
* Contract duration acts as a strong retention mechanism.

---

### 3. Senior Citizens are a High-Risk Segment

**Observation**

* Senior citizens churn at a higher rate compared to non-senior customers.

**Business Interpretation**

* Possible issues include:

  * Service complexity
  * Pricing concerns
  * Customer support experience

---

### 4. Value-Added Services Improve Retention

Customers subscribed to the following services demonstrate substantially lower churn:

* Online Security
* Online Backup
* Device Protection
* Tech Support

**Business Interpretation**

* Additional services increase customer engagement and dependency on the telecom ecosystem.

---

### 5. Payment Method Influences Churn

**Observation**

* Electronic Check users show significantly higher churn rates compared to other payment methods.

**Possible Reasons**

* Less automated payment process
* Lower customer commitment
* Higher likelihood of payment friction

---

### 6. Gender Has Minimal Impact

**Observation**

* Male and female customers display similar churn behavior.

**Business Interpretation**

* Gender-based retention strategies are unlikely to generate meaningful improvements.

---

## 📊 Visualizations

### Customer Churn Distribution

*Insert chart screenshot here*

```
images/churn_distribution.png
```

---

### Tenure vs Churn

*Insert chart screenshot here*

```
images/tenure_churn.png
```

---

### Contract Type vs Churn

*Insert chart screenshot here*

```
images/contract_churn.png
```

---

### Payment Method vs Churn

*Insert chart screenshot here*

```
images/payment_method_churn.png
```

---

### Senior Citizen Churn Analysis

*Insert chart screenshot here*

```
images/senior_citizen_churn.png
```

---

### Value-Added Services Analysis

*Insert chart screenshot here*

```
images/value_added_services.png
```

---

## 🚨 High-Risk Customer Segmentation

The analysis identified a customer profile with significantly elevated churn risk.

### High-Risk Customer Characteristics

✅ Month-to-month contract

✅ Tenure less than 6 months

✅ Electronic Check payment method

✅ Senior citizen

✅ No subscription to:

* Online Security
* Online Backup
* Tech Support
* Device Protection

### Retention Priority

Customers exhibiting multiple characteristics from the above list should be proactively targeted by retention teams.

---

## 💡 Strategic Recommendations

### 1. Implement a 90-Day Onboarding Program

**Goal**
Reduce early-life churn.

**Actions**

* Welcome campaigns
* Personalized onboarding
* Proactive customer support
* Usage guidance

**Expected Impact**

* Improved customer experience
* Increased retention among new users

---

### 2. Convert Month-to-Month Customers

**Goal**
Increase long-term commitment.

**Actions**

* Annual contract discounts
* Loyalty rewards
* Contract upgrade campaigns

**Expected Impact**

* Lower churn probability
* Higher customer lifetime value

---

### 3. Promote Value-Added Services

**Goal**
Increase customer engagement.

**Actions**

* Bundle security and support services
* Offer introductory discounts
* Cross-sell during onboarding

**Expected Impact**

* Stronger customer dependency
* Increased retention

---

### 4. Target Electronic Check Users

**Goal**
Reduce payment-related churn.

**Actions**

* Encourage auto-pay enrollment
* Provide payment incentives
* Promote digital payment methods

**Expected Impact**

* Lower churn risk
* Improved payment consistency

---

### 5. Create Senior Citizen Support Programs

**Goal**
Improve retention among vulnerable customer groups.

**Actions**

* Simplified plans
* Dedicated support channels
* Easy-to-understand billing

**Expected Impact**

* Better customer satisfaction
* Reduced churn among senior customers

---

## 🛠️ Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Computing       |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Jupyter Notebook | Analysis Environment      |
| Scikit-learn     | Machine Learning Support  |
| Git & GitHub     | Version Control           |

---

## ▶️ How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/telecom-customer-churn-analysis.git
```

### Navigate to Project Folder

```bash
cd telecom-customer-churn-analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
TelecomChurnAnalysis.ipynb
```

---

## 📁 Project Structure

```text
telecom-customer-churn-analysis/
│
├── TelecomChurnAnalysis.ipynb
├── telecom_customer_churn.csv
├── README.md
│
├── images/
│   ├── churn_distribution.png
│   ├── tenure_churn.png
│   ├── contract_churn.png
│   ├── payment_method_churn.png
│   ├── senior_citizen_churn.png
│   └── value_added_services.png
│
└── requirements.txt
```

---

## 📌 Results & Conclusion

This analysis identified several strong predictors of customer churn:

* Short customer tenure
* Month-to-month contracts
* Electronic Check payment methods
* Senior citizen status
* Lack of value-added services

The current churn rate of **26.54%** indicates a substantial opportunity for retention improvement.

By focusing on:

* Early customer onboarding,
* Contract conversion strategies,
* Service bundling,
* Payment optimization,
* Senior citizen support initiatives,

telecom providers can reduce churn, improve customer lifetime value (CLV), and increase long-term revenue stability.

---

## 📜 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project with proper attribution.

---

## 👩 Author

**Bhumika Maji**

Data Analytics Enthusiast | SQL | Python | Data Visualization

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

⭐ If you found this project useful, consider giving it a star!
