# 🏦 Bank Loan Analysis Report (Power BI )

This project is a comprehensive Bank Loan Analysis Report built using  **Power BI** for visualization and analysis. The primary goal is to provide critical insights into the bank's lending portfolio, assess risk, and enable data-driven decision-making.

---

##  Project Objectives

* **Assess Portfolio Health:** Monitor the overall performance and risk profile of the loan portfolio.
* **Track Key Metrics:** Calculate and monitor core Key Performance Indicators (KPIs) like total applications, funded amounts, and interest rates.
* **Time-Series Analysis:** Analyze performance trends using Month-to-Date (MTD) and Month-over-Month (MoM) metrics for all key indicators.
* **Detailed Insights:** Create a consolidated 'Details Dashboard' for accessing vital loan data, borrower profiles, and individual loan performance.

---

## Key Performance Indicators (KPIs) Monitored

The report tracks five essential KPIs, including their MTD values and MoM changes:

1.  **Total Loan Applications:** Total count of applications received.
2.  **Total Funded Amount:** Total amount of funds disbursed as loans.
3.  **Total Amount Received:** Total amount collected from borrowers.
4.  **Average Interest Rate:** Overall average interest rate across the portfolio.
5.  **Average Debt-to-Income (DTI) Ratio:** Average DTI to gauge borrower financial health.

---

##  Dashboard Structure

The project is structured around a multi-page report:

### 1. Summary Dashboard

* **Core KPIs:** Display of the five main KPIs with MoM trend indicators.
* **Good Loan vs Bad Loan Analysis:** A side-by-side comparison of 'Good Loan' and 'Bad Loan' performance based on Application Percentage, Applications, Funded Amount, and Total Received Amount.
* **Loan Status Grid View:** A comprehensive table categorized by **'Loan Status'** (e.g., Fully Paid, Current, Default) showing key metrics for each status.

  <img width="1431" height="801" alt="Summary" src="https://github.com/user-attachments/assets/e48c63fa-09e9-4e9d-b0a9-c106cd00dd02" />

  <img width="1435" height="801" alt="Overview" src="https://github.com/user-attachments/assets/e4f5a0e9-5613-460f-b761-efd5ca02eba6" />



### 2. Details Dashboard

* **Grid View:** Provides a consolidated, holistic snapshot of all key loan-related metrics and data points.
* **Objective:** Offers a user-friendly interface for detailed insights into the loan portfolio, borrower profiles, and individual loan performance.

<img width="1430" height="801" alt="Details" src="https://github.com/user-attachments/assets/19f5c835-a11a-4c59-8c7a-d584d47fb4e0" />


## 🛠 Technologies and Skills Used

This project showcases expertise in data engineering, modeling, and visualization:

### Power BI (Data Visualization & Analysis)

* **Connectivity & Preparation:** Connecting to SQL Server, Data Cleaning, Power Query.
* **Modeling & DAX:** Data Modelling, Time Intelligence Functions, DAX (Data Analysis Expressions).
* **Visualization:** Creating KPIs, New Card Visuals, Charts, Formatting visuals, and Navigations.
* **Core Functions:** `CALCULATE`, `SUM`/`SUMX`, Date Function, Text Function, Filter Function.


## 📚 Key Data Terminology

The analysis relies on understanding key fields used for risk assessment and performance tracking:

| Field | Description | Bank Use |
| :--- | :--- | :--- |
| **Loan Status** | Current state of the loan (e.g., current, default, fully paid). | Monitoring loan health and risk analysis. |
| **DTI** | Debt-to-Income Ratio (Debt burden relative to income). | Assessing borrower capacity to handle payments. |
| **Grade/Sub Grade** | Risk classification based on creditworthiness. | Pricing loans and tailoring interest rates to risk profiles. |
| **Annual Income** | Borrower's total yearly earnings. | Determining loan eligibility and evaluating creditworthiness. |
| **Home Ownership**| Borrower's housing status. | Assessing collateral availability and borrower stability. |
