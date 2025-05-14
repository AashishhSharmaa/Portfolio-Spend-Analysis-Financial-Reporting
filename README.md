# Portfolio Spend Analysis FY2024-25: Financial-Reporting

![main](https://github.com/user-attachments/assets/b5c79130-d017-4033-93e9-c900357db907)

## **1. Introduction**

This project showcases a financial analysis exercise using Excel, focused on forecasting and actual spend tracking for a portfolio of projects. The core of the analysis involves understanding cash flow (CF) and expense (PL) trends across various business lines and project types.

## **2. Objective**

To analyze and visualize the financial performance of a project portfolio by:

1.	Creating a single pivot table showing actual and forecasted cash flow (CF) and expenses (PL) monthly.

2.	Developing a presentation-level dashboard and slide deck with:

    o	A full-year forecast graph.

    o	Charts by business line and project type.

    o	Key insights derived from the data.

3.	Answering two business-critical questions related to budget variance and forecast anomalies.

## **3. Dataset Provided**

A raw dataset containing full-year financial forecasts and actuals across multiple projects. It includes:
•	Cash Flow (CF): Total spend on a project, including resource costs, capital expenditure, and other expenses.
•	Expense (PL): A subset of CF, reflecting the actual operating expenses only.

![0  Data Set](https://github.com/user-attachments/assets/e38b235e-4c8c-4ab9-9c5a-fda7a04864b4)

⚠️ Figures in past months = actuals; figures in future months = forecasts.

## **4. Requirements**

Part 1.	A single pivot table displaying both CF and PL across months and FY totals (in millions (MM)).

Part 2.	A dashboard slide including:
o	FY forecast graph (CF & PL)
o	Charts for breakdown by business line and project type
4.	Key insights from the analysis.

Part 3.	Responses to:
o	Which business line/team had the biggest variance?
o	Any project with unusual forecasting?

## **🛠️ 5. Solution**

### **Section 1: Pivot Table – Data Transformation and Modeling**

•	Started with data cleaning and transformation of the raw dataset.
•	Wrote DAX formulas and applied calculated columns to extract monthly breakdowns and yearly totals.
•	Final dataset saved as: "Data (Transformed)", fully ready for visualization and pivoting.

![0 1 Data  Transformed](https://github.com/user-attachments/assets/43864ff6-426d-4433-a35f-1d097bdc392a)

### **Pivot Table: Monthly Forecast and Actual Spend by Project (CF & PL)**

This pivot table showcases the monthly forecast and actual spend by project, where:
•	November 2024 – April 2025 represents actuals
•	May 2025 – October 2025 represents forecasts

![1  Pivot Table p1](https://github.com/user-attachments/assets/4d69f0dd-ad3a-413e-af7b-e40e4bb53094)
![2  Pivot Table p2](https://github.com/user-attachments/assets/d3e28d17-a359-49c2-a9ec-8e58e253bb5a)

### **Section 2: Dashboard – FY2024–25 Portfolio Spend Analysis**

This dashboard includes:
1.	A full-year line graph comparing CF vs PL
2.	Different visuals to display Key insights from trends, spikes, and variances for Business Lines and Project Type.

![image](https://github.com/user-attachments/assets/99d3ba50-fc3d-43e6-8771-9f2c10fc4890)

### **Section 3: Additional Business Questions**

**Q1. Which business line / team had the biggest variance between budget and spend?**

**Answer:** Fraud team had the highest variance with an underspend of -$48.21M from the allocated $100.28M budget.

![4  Q1 addiitonal Question](https://github.com/user-attachments/assets/3c1b884f-4f0b-4791-9b58-4d8a1ff8300c)

**Q2. Any project with forecast irregularity?**

**Answer:** Project G stood out to me due to a significant irregularity in the forecast. In August 2025, the forecasted cash flow was $0.064 million, while expenses were projected at $1.981 million. Then, in September, cash flow jumped to $2.690 million, creating a notable discrepancy in the projections.

The irregularity could be primarily due to large upfront expenses, such as vendor payments, equipment costs or software purchase, being forecasted for August 2025.  This creates a temporary cash flow gap in the forecast for the Q4.

**Project G showed a notable irregularity:**

![5  Part 1](https://github.com/user-attachments/assets/21e6082f-b27d-4c9d-96bd-18279e515711)

**August 2025: CF = $0.064M | PL = $1.981M**

![5  Q2 - Cash Flow](https://github.com/user-attachments/assets/877037ec-9838-4526-b14f-59d215119b68)

**September 2025: CF jumps to $2.690M**

![6  Q2-Expense](https://github.com/user-attachments/assets/e52bdf0e-203d-4d68-a37a-52843129692b)

## **6. Conclusion**

The financial reporting dashboard successfully consolidates full-year forecasts, offering clear visibility into actuals vs forecasted spend. It helps identify spending inefficiencies, track project costs, and inform budgeting decisions.

## **7. Key Skills Demonstrated**

•	Data Cleaning & Transformation in Excel

•	Pivot Table Design

•	Dashboard Creation & Data Storytelling

•	Financial Forecasting & Budget Analysis

•	Business Insight Generation

•	Communication of Findings via Slide Deck
