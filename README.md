# Sales Method Analysis and Recommendations
### Project Overview 

   This project analyzes various sales methods and their impact on customer engagement and revenue generation. The goal is to uncover the best sales strategies and provide actionable recommendations to enhance future sales efforts.

## Table of Contents
Introduction
Data Validation and Cleaning
Sales Performance Metrics
Exploratory Sales Analysis
Recommendations
Monitoring Plan
## Introduction
In this analysis, I evaluated the effectiveness of three sales methods—email, call, and a combination of both—in terms of customer count and revenue generation. The findings aim to inform data-driven decisions for improving sales strategies and driving growth.

## Data Validation and Cleaning
The dataset initially contained several inconsistencies:

* **Missing Data**: 1,074 entries in the revenue column were filled using the mean value.
* **Data Formatting**: The week column, initially in integer format, was converted to a date-time format.
* **Sales Method Standardization**: Inconsistent entries in the sales method column (e.g., 'Email', 'em + call', 'Call') were standardized to ['email', 'email & call', 'call'] for consistency.
## Sales Performance Metrics
Key sales metrics were used to assess the success of each method:

* **Customer Count**: The email-only method was the most effective in attracting customers with minimal effort.
* **Revenue Distribution**: A bimodal revenue distribution was observed, with peaks at 40-50 and 90-100. The "email & call" method generated the highest median revenue, making it ideal for high-value leads.

## Exploratory Sales Analysis
1. Customer Count by Sales Method:

      * Email-only: Proved to be highly efficient for broad outreach with minimal resources.
2. Revenue by Sales Method:

    * Email & Call: Showed the highest median revenue, making it ideal for high-value, high-effort sales.
    * Call-only: Had high initial returns but lacked long-term sustainability.
3. Revenue Over Time:
    * The call method was effective for short-term campaigns, while email & call demonstrated consistent growth over time.
      
## Recommendations
* **Email-only**: Best for broad customer reach with minimal effort. Continue using this for general outreach and maintaining customer engagement with low resources.
* **Email & Call**: Best for driving higher revenue. Prioritize this method for high-value leads, as it balances higher returns with moderate effort.
* **Call-only**: Effective for high-priority short-term campaigns, but not ideal for long-term sustainability.
##Monitoring Plan
To ensure continued success, I recommend monitoring the **Average Revenue per Sales Method** on a weekly or monthly basis. Regular tracking will allow the business to:

* Identify trends.
*Adjust strategies to focus on the most successful methods.
### Key Takeaways:

* If "Email & Call" continues delivering significantly higher revenue, invest more in this method.
* If the simpler "Email" method shows strong performance, it could be an efficient option for customer engagement.
