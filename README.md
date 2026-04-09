# lendingclub-credit-risk-analysis
End-to-end fintech credit risk assessment of 1.2M+ LendingClub loans. Leveraging Python and SQL, this project identifies critical default triggers and validates credit grading models. Includes a comprehensive Tableau executive dashboard to optimize corporate underwriting policies and protect ROI.
# LendingClub Portfolio Analysis: Credit Risk Assessment

## Executive Summary
This project is a comprehensive credit risk assessment focused on the fintech lending space. Leveraging a historical dataset of over 1.27 million consumer loans from LendingClub, the primary objective was to audit default exposure and isolate risk triggers to optimize credit origination policies.

## Tech Stack
* **Data Wrangling & Processing:** Python (Pandas, NumPy)
* **Exploratory Data Analysis:** SQLite
* **Business Intelligence & Visualization:** Tableau

## Key Findings
* **Portfolio Baseline:** Identified a historical global default rate of 19.5% across the portfolio.
* **Grading Model Efficacy:** Validated the internal credit grade system, proving risk scales predictably from Grade A (5.75% default) to Grade G (49.54% default).
* **Term-Based Risk:** Revealed that 60-month loans carry a disproportionately higher risk (32.07% default rate) compared to 36-month loans (15.43%).
* **Purpose-Based Risk:** Identified 'Small Business' funding as the riskiest category with a nearly 30% probability of default.

## Interactive Dashboard
The final executive dashboard detailing these insights, designed for stakeholder decision-making, can be found here: 
**https://public.tableau.com/views/LendingClubCreditRiskAnalysis_17756666036330/Dashboard?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

## Repository Contents
The entirety of the data cleaning, exploratory data analysis, business logic, and link to the visualization are contained within a single Python notebook: **https://www.kaggle.com/code/mvillarreal03/lendingclub-credit-risk-analysis**.
