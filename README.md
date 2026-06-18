# Hospital-Revenue-Cycle-Optimization
An end-to-end healthcare analytics project using Excel Power Query and Tableau to analyze $790K in insurance claim denials and optimize hospital operational revenue.
## 🔗 Interactive Tableau Dashboard
👉 **[View the Live Tableau Dashboard Here](https://public.tableau.com/app/profile/christian.austin)**
## 📊 Dashboard Preview
![Hospital Revenue Dashboard](dashboard_screenshot.png)

## Project Overview
This project focuses on a major operational issue in healthcare administration: unpaid insurance claims. Using a raw public dataset of patient billing logs, I wanted to find out exactly where the hospital was losing money, which departments had the highest rejection rates, and what specific billing errors were causing the problem.

## Tools I Used
* **Excel Power Query:** Importing, cleaning, and preparing the raw data
* **Excel Pivot Tables:** Finding the baseline totals, denial rates, and sorting the data
* **Tableau:** Building the interactive dashboard, KPI cards, and visual charts

## Key Insights from the Data
* **The Financial Impact:** The dataset showed a **29.8% baseline claim denial rate**, which leaves **$790,885.94 in delayed revenue** sitting unpaid by insurance companies.
* **The Main Offender:** When I broke the data down by clinical specialties, the **General Practice Department** was responsible for the largest chunk of the loss, driving **27.35% ($216,307.30)** of the total revenue leaks.
* **The Root Cause:** By tracking both the volume (count) and severity (dollar sum) of the medical codes, I isolated **Procedure Code EY943** as the highest-denied procedure. This indicates a specific systemic issue with how this procedure is being documented during the patient intake process.

## Actionable Recommendations
1. **Fix Front-End Data Entry:** Add mandatory field validations in the patient registration software for General Practice staff. Catching missing documentation before a claim is submitted directly prevents insurance rejections.
