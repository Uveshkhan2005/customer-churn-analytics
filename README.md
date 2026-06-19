# Customer Churn Analytics

## Project Overview

Customer Churn Analytics is an end-to-end Data Analytics project focused on understanding customer behavior and identifying the factors that contribute to customer churn.

The project analyzes customer demographics, service subscriptions, contract information, billing patterns, and customer tenure to uncover actionable business insights that can improve customer retention and reduce revenue loss.

---

## Business Problem

Customer churn is one of the most critical challenges for subscription-based businesses. Acquiring a new customer is often more expensive than retaining an existing one.

This project aims to answer key business questions:

* What percentage of customers churn?
* Which customer groups are most likely to leave?
* How does customer tenure affect churn?
* Which contract types have the highest retention rates?
* Does internet service type impact churn?
* Which payment methods are associated with higher churn rates?
* What business actions can reduce churn?

---

## Dataset Information

**Dataset:** Telco Customer Churn Dataset

**Source:** IBM Sample Data

**Records:** 7,043 Customers

**Features:** 21 Variables

**Target Variable:** Churn (Yes / No)

### Key Columns

* Customer Demographics

  * Gender
  * Senior Citizen
  * Partner
  * Dependents

* Customer Services

  * Phone Service
  * Internet Service
  * Online Security
  * Tech Support
  * Streaming TV
  * Streaming Movies

* Account Information

  * Contract Type
  * Payment Method
  * Monthly Charges
  * Total Charges
  * Tenure

---

## Tools & Technologies

### Programming

* Python
* SQL

### Python Libraries

* Pandas
* NumPy
* Matplotlib

### Analytics & Visualization

* Excel
* Power BI
* Jupyter Notebook

### Version Control

* Git
* GitHub

---

## Project Workflow

### Phase 1: Data Exploration ✅

* Dataset Loading
* Shape Analysis
* Data Type Inspection
* Descriptive Statistics
* Churn Distribution Analysis

### Phase 2: Data Cleaning ✅

* Missing Value Detection
* Hidden Missing Value Identification
* TotalCharges Data Type Correction
* Removal of Invalid Records
* Dataset Quality Assessment

### Phase 3: Exploratory Data Analysis (In Progress)

* Churn by Gender
* Churn by Senior Citizen Status
* Churn by Contract Type
* Churn by Internet Service
* Churn by Payment Method
* Customer Tenure Analysis

### Phase 4: Data Visualization

* Customer Churn Dashboard
* Business Insight Charts
* KPI Analysis

### Phase 5: Power BI Dashboard

* Executive Summary Dashboard
* Churn Monitoring Dashboard
* Customer Segmentation Dashboard

---

## Data Cleaning Findings

During the data quality assessment:

* No explicit null values were found.
* The TotalCharges column was stored as an object data type.
* 11 records contained blank TotalCharges values.
* These records belonged to customers with zero tenure.
* Invalid records were removed.
* TotalCharges was successfully converted to numeric format.

### Dataset After Cleaning

* Original Records: 7,043
* Removed Records: 11
* Final Records: 7,032

---

## Current Progress

### Repository Setup

* [x] GitHub Repository Created
* [x] Dataset Uploaded

### Data Exploration

* [x] Dataset Inspection
* [x] Data Summary
* [x] Churn Distribution Analysis

### Data Cleaning

* [x] Missing Value Analysis
* [x] Hidden Missing Value Detection
* [x] TotalCharges Conversion
* [x] Data Quality Assessment

### Exploratory Data Analysis

* [ ] Churn by Gender
* [ ] Churn by Contract Type
* [ ] Churn by Internet Service
* [ ] Churn by Payment Method
* [ ] Tenure Analysis

### Dashboard Development

* [ ] Power BI Dashboard
* [ ] KPI Cards
* [ ] Executive Summary

---

## Key Initial Findings

### Churn Distribution

| Metric             | Value  |
| ------------------ | ------ |
| Total Customers    | 7,043  |
| Retained Customers | 5,174  |
| Churned Customers  | 1,869  |
| Churn Rate         | 26.54% |

### Business Insight

Approximately **1 out of every 4 customers** has churned, indicating a significant customer retention challenge and highlighting the need for deeper analysis into customer behavior and service usage patterns.

---

## Repository Structure

customer-churn-analytics/

├── dataset/

├── notebooks/

├── sql/

├── visuals/

├── powerbi/

├── report/

└── README.md

---

## Upcoming Analysis

The next phase of the project will focus on identifying customer segments with the highest churn rates and discovering the strongest predictors of customer attrition.

---

## Author

### Uveshkhan Lohani

BE Information Technology Graduate

Aspiring Data Analyst

Skills:

* Python
* SQL
* Excel
* Power BI
* Pandas
* NumPy
* Data Visualization

Currently building end-to-end Data Analytics projects and sharing them on GitHub.
