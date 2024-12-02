# Bank Churn Analysis Dashboard

## Overview

This repository contains the Power BI dashboard for analyzing customer churn in the banking sector. The dashboard aims to provide actionable insights into customer behavior, identify factors influencing churn, and support strategic decision-making to enhance customer retention.

**Access the live dashboard here:** [Bank Churn Analysis Dashboard](https://app.powerbi.com/groups/me/reports/69407628-720e-4653-93ce-7c0df320e8bb/00416c7859a9b6b97228?experience=power-bi)

---

## Features

- **Customer Insights:** Analyze customer demographics, including geography, age, and gender.
- **Churn Drivers:** Identify key factors that contribute to customer churn, such as credit score, balance, and activity status.
- **Financial Metrics:** Overview of average balances, estimated salaries, and point-based rewards.
- **Interactive Filters:** Drill down into specific customer segments for targeted insights.

---

## Dataset Details

### Data Summary
The dataset consists of 10,000 records and 18 columns, detailing customer information and activity. Below are the key features:

- **Demographics:** `CustomerId`, `Surname`, `Geography`, `Gender`, `Age`
- **Financial Data:** `CreditScore`, `Balance`, `EstimatedSalary`
- **Account Information:** `Tenure`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`
- **Churn Metrics:** `Exited` (churn indicator)
- **Feedback:** `Complain`, `Satisfaction Score`
- **Rewards:** `Card Type`, `Point Earned`

### Sample Data
| RowNumber | CustomerId | Geography | Gender | Age | CreditScore | Balance  | Exited |
|-----------|------------|-----------|--------|-----|-------------|----------|--------|
| 1         | 15634602   | France    | Female | 42  | 619         | 0.00     | 1      |
| 2         | 15647311   | Spain     | Female | 41  | 608         | 83807.86 | 0      |
| 3         | 15619304   | France    | Female | 42  | 502         | 159660.8 | 1      |

---

## Dashboard Visuals

The Power BI dashboard includes the following:

1. **Customer Segmentation:** Charts for demographics like gender, geography, and age group.
2. **Churn Metrics:** Visualizations of churned vs. active customers and trends over time.
3. **Financial Overview:** Average account balances and customer credit scores.
4. **Customer Activity:** Satisfaction scores and product usage metrics.

---

## How to Use

### Online Access
Interact with the dashboard directly using the [live link](https://app.powerbi.com/groups/me/reports/69407628-720e-4653-93ce-7c0df320e8bb/00416c7859a9b6b97228?experience=power-bi).

### Local Access
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bank-churn-dashboard.git
2. Open the `Bank-Churn.pbix` file in Power BI Desktop.
3. Explore the dashboard using slicers and filters

---

## Contributions

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a branch:
   ```bash
   git checkout -b feature-name
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
4. Push and open a pull request.

---

## License

This project is licensed under the MIT License.


