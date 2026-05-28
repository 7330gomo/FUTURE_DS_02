# FUTURE_DS_02

# Customer Subscription Churn Analysis

## Project Overview

This project focused on analyzing customer subscription behaviour to understand patterns related to churn, retention, customer engagement, and subscription performance. The analysis examined customer activity across different subscription plans, usage levels, payment behaviours, support requests, and customer lifecycle stages to identify factors influencing customer retention and cancellations.

The project aimed to provide data-driven insights that can help businesses improve customer satisfaction, reduce churn, and support long-term customer growth.

---

# Project Objectives

* Analyze customer churn and retention trends across subscription plans.
* Identify factors contributing to customer cancellations.
* Evaluate customer engagement using usage behaviour and login activity.
* Perform cohort analysis to understand customer behaviour over time.
* Examine customer lifecycle stages and loyalty patterns.
* Identify high-risk customer groups that require retention strategies.
* Provide actionable recommendations to improve customer retention and subscription performance.

---

# Tasks Performed

* Conducted churn rate analysis by:

  * Subscription plan
  * Support tickets
  * Payment failures
  * Average weekly usage

* Performed retention analysis based on:

  * Customer tenure
  * Subscription plans
  * Usage categories
  * Monthly customer activity

* Conducted customer cohort analysis using:

  * Signup months
  * Tenure categories
  * Usage behaviour
  * churn rate

* Analyzed customer lifetime patterns and loyalty behaviour.

* Compared customer behaviour across multiple customer segments and time periods.

---

# Tools Used

* SQL- for querying the data
* Tableau for visualization
* Powerpoint -for presentation


---

# Exploratory Data Analysis (EDA)

The exploratory analysis focused on understanding the structure and quality of the dataset before performing business analysis.

The following checks and investigations were performed:

* Viewing all dataset records
* Identifying distinct values across columns
* Checking for missing/null values
* Extracting month and year from signup dates
* Exploring customer subscription plans
* Examining payment failures and support requests
* Reviewing customer usage behaviour
* Investigating churn and retention distributions

The dataset included the following key fields:

* User ID
* Signup Date
* Subscription Plan
* Monthly Fee
* Average Weekly Usage Hours
* Support Tickets
* Payment Failures
* Tenure Months
* Retention rate
* Churn Status

---

# Data Transformation

Several data transformation techniques were applied using SQL CASE statements and aggregations to improve analysis and reporting.

1. Usage Categories

Customers were grouped into usage categories such as:
* No usage
* Very low usage
* Low usage
* Moderate usage
* High usage
* Power users
* Extreme usage

2. Support Ticket Categories

Support requests were categorized into:
* 0 tickets
* 1 ticket
* 2 tickets
* 3 tickets
* 4 tickets
* 5 tickets
* 6 tickets
* 7 tickets
* 8 tickets
* 9+ tickets

3. Payment Failure Categories

Payment behaviour was grouped into:
* No failures
* 1 failure
* 2 failures
* 3 failures
* 4 failures
* 5 failures
* 5+ failures

4. Customer Lifecycle Stages

Customers were grouped according to tenure:
* New users
* Early-stage users
* Developing users
* Established users
* Loyal users
* Long-term users

---

# Data Visualization Focus Areas

The analysis focused on visualizing:

* Churn rate by subscription plan
* Retention rate by customer lifecycle stage
* Churn trends across months
* Customer growth trends
* Customer cohort behaviour
* Support ticket impact on churn
* Payment failure impact on churn
* Usage behaviour and engagement patterns
* Customer lifetime patterns
* Loyalty and retention comparisons

---

# Key Insights

* The business experienced steady customer growth between January and July.
* The Standard plan consistently attracted the highest number of customers.
* Loyal users formed the largest and most stable customer segment.
* Churn rates remained relatively high and stable across months.
* Churn was distributed across all subscription plans rather than being concentrated in a single plan.
* Customers with multiple support requests showed higher churn behaviour.
* Payment failures were strongly associated with customer cancellations.
* Customers with very high usage levels were more likely to churn, suggesting possible dissatisfaction among highly engaged users.
* Loyal and established customers showed the strongest retention rates.
* New and early-stage users consistently had the weakest retention rates.
* Low-usage customers demonstrated lower engagement and weaker retention.

---

# Recommendations

* Strengthen customer retention strategies by focusing on high-risk groups such as heavy users, customers with multiple support requests, and users experiencing payment failures.
* Improve onboarding and early-stage customer engagement through tutorials, guided onboarding, and targeted communication.
* Enhance customer support quality and issue resolution processes to reduce customer dissatisfaction.
* Optimize payment systems by introducing automated reminders, retry mechanisms, and flexible payment options.
* Maintain the strong value offering of the Standard plan and loyal-user segments.
* Improve the attractiveness of Basic and Premium plans through tailored features and pricing strategies.
* Increase customer acquisition efforts to attract more new users.
* Improve engagement among low-usage customers through personalized recommendations and educational campaigns.

---

# Conclusion

The analysis revealed that the business has a strong and growing customer base, particularly within the Standard subscription plan and loyal-user segments. Loyal customers contribute significantly to retention and long-term business stability.

However, customer churn remains a major challenge across all subscription plans. Factors such as payment failures, multiple support requests, and dissatisfaction among highly engaged users appear to contribute significantly to customer cancellations.

The findings also show that the business performs well at retaining long-term customers but struggles to maintain engagement among new and early-stage users. Additionally, low customer engagement levels negatively impact retention performance.

Overall, improving customer onboarding, customer support quality, payment reliability, and engagement strategies will be essential for reducing churn, improving customer satisfaction, and supporting sustainable long-term business growth.

---

