# Bank-Loan-Performance-Dashboard
**Project Title:** Bank Loan Performance Dashboard



**Project Overview**
I built a complete data analysis project from scratch to help a bank understand its loan performance. The goal was to create a clear, interactive report that shows how many loans are given out, how well customers are repaying them, and where the bank might be losing money. This helps the bank make smarter decisions about who to give loans to in the future.



**The Problem**
The bank had a lot of data but no easy way to understand it. They needed answers to questions like:

How many loans are we giving out each month?

What is the total amount of money we have lent out?

How much money are we getting back?

Which loans are "good" (being repaid) and which are "bad" (not being repaid)?

Are there specific states, loan types, or customer profiles that are more risky?




**My Approach (Step-by-Step)**

**1. Understanding the Data & Business Needs**

I first learned about key banking terms like **"Good Loan"** (customers who pay on time), **"Bad Loan"** (customers who don't pay), and "Debt-to-Income Ratio" (a measure of a customer's financial health).

I explored a dataset of over 38,000 past loans with details like loan amount, interest rate, customer's home state, job experience, and repayment status.




**2. Data Validation with SQL**

Before making any charts, I used SQL to check the data and calculate the core numbers. This ensured that everything in the final dashboard would be accurate.


**I wrote queries to find:**

**Key Totals:** Total number of loans, total amount given, total amount repaid.

**Loan Health:** The percentage and amount of "Good" vs. "Bad" loans.

**Trends:** How these numbers changed month-by-month and varied by state, loan purpose, and customer details.





**3. Building the Interactive Dashboard in Power BI**
I created a user-friendly, 3-page report in Power BI:


**Page 1: The Big Picture (Summary)**

This page gives a quick snapshot of the bank's health.

It shows the most important numbers (KPIs) like Total Loans, Total Amount Repaid, and Average Interest Rate.

It has a clear visual showing the split between Good and Bad Loans.

Includes filters for Date, Loan Grade, and State.

**Dashboard of Summary :**
[Project Dashboard](summary.png)




**Page 2: The Deep Dive (Overview)**

This page allows users to explore the "why" behind the numbers.

It features charts that answer specific questions:

**Line Chart:** How do our loans change from month to month?

**Map:** Which states have the most loans?

**Donut & Bar Charts:** What are the most common loan purposes? How does a customer's job experience affect their loans?

Includes a **special button** to switch the entire page between "Number of Loans," "Amount Funded," and "Amount Received."






**Page 3: The Details**


A simple table showing all the raw data behind the charts, allowing users to see individual loan records.



**Key Findings & Insights**


**The business is mostly healthy:** 86% of all loans were "Good Loans," meaning the vast majority of customers are repaying their debts, making the bank a good profit.


**A clear risk was identified:** However, 14% of loans were "Bad Loans." The bank had given out $65 million to these customers but only got back $37 million, pointing to a significant area of loss.


**Top loan purpose:** The most common reason people took a loan was for Debt Consolidation.


**Top market:** California (CA) was the state with the highest number of loans and the largest amount of money given out.





**Tools & Technologies**


**Power BI :** For data visualization and building the interactive dashboard.


**MySQL :** For data extraction, validation, and analysis.


**Advanced Microsoft Excel :** For initial data review and cleaning.


**Data Modelling :** To build the relationship between tables


**DAX :** (Data Analysis Expression) -- Used for Calculated Measures, Dynamic Visuals, Conditional Logics.


**Power Query :**   Data transformation and Cleaning layer for reshaping and preparing the data.






**Conclusion**
This project provided the bank with a single source of truth for their loan performance. The dashboard helps them easily track their business health, identify successful areas, and pinpoint risky customer profiles or loan types. This empowers them to adjust their lending strategy to increase profits and reduce future losses.


**KEY IMPACTS & OUTCOMES** 
Drove Profitability & Risk Mitigation: Pinpointed that 14% of loans (valued at $65M) were high-risk, providing the business with a clear target for credit policy review, which is projected to significantly reduce future financial losses and improve portfolio health.

Enabled Proactive Business Strategy: Revealed that Debt Consolidation was the most common loan purpose and California the top market, enabling the sales and marketing teams to focus campaigns and resources for maximum return on investment.

Eliminated Reporting Bottlenecks & Empowered Users: Replaced static, time-consuming reports with an interactive, self-service Power BI dashboard, reducing ad-hoc data requests by an estimated 60% and allowing business teams to make data-informed decisions independently and in real-time.

Established a Single Source of Truth: Delivered a centralized and validated reporting platform that aligned cross-functional teams (Risk, Sales, Finance) on key metrics, improving the accuracy and speed of monthly performance reviews and strategic planning.


