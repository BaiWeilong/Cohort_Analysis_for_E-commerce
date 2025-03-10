# Cohort Analysis for E-commerce

This repository contains tools and scripts for performing Cohort Analysis in the e-commerce sector. 
The main goal of the project is to study customer behavior, assess retention rates, and identify trends in repeat purchases.

![cohort_analysis_dashboard](https://github.com/user-attachments/assets/cohort_dashboard_example.png)

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data Requirements](#data-requirements)
- [Cohort Analysis Methodology](#cohort-analysis-methodology)
- [Results](#results)

---

## Introduction

Cohort analysis helps evaluate how long customers remain active and what factors influence their behavior.
The method involves segmenting users into cohorts based on the date of their first purchase and tracking their activity in subsequent months.

This project enables:
- Evaluating customer retention rates.
- Analyzing changes in user behavior over time.
- Developing strategies to enhance customer loyalty.

---

## Features

- Data loading and cleansing.
- Generation of cohort tables.
- Calculation of retention rates.
- Visualization of results using heatmaps.
- Data interpretation for business decision-making.

---

## Data Requirements

The input dataset should contain the following columns:

| Column Name   | Description                        |
|--------------|----------------------------------|
| InvoiceDate  | Date and time of the transaction. |
| Customer ID  | Unique customer identifier.       |
| Quantity     | Number of purchased items.        |
| Price       | Price per item.                    |

The file should be in CSV format, without duplicates, and with correct values.

---

## Cohort Analysis Methodology

1. **Data loading and cleaning**: Removing missing values, duplicates, and anomalies.
2. **Cohort identification**:
   - Assigning each purchase to the month of the customer's first order.
   - Forming cohort groups.
3. **Retention rate calculation**:
   - Counting the number of customers remaining active in each subsequent month.
   - Generating a retention matrix.
4. **Visualization**:
   - Creating heatmaps to analyze customer retention trends.

---

## Results

- **Understanding customer behavior**: Identifying which cohorts remain active the longest.
- **Identifying trends**: Analyzing the impact of seasonality and marketing campaigns.
- **Optimizing retention strategies**: Recommendations for improving customer engagement.

This analysis helps businesses increase repeat purchase conversion rates and enhance customer interaction.

---

### 🚀 How to Use?

1. Prepare a CSV file with order data.
2. Run `cohort_analysis_ecommerce.py` to process the data.
3. Review the visualization and gain insights for marketing strategies.

---

**🔍 Ready to analyze?** Start now! 📊
