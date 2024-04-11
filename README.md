# BANK_CUSTOMER CHURN ANALYSIS

**CUSTOMER CHURN ANALYSIS**

## Introduction

In this project, we want to analyze bank customer data to find out why consumers quit the bank.

customer Churn is an important part of any business. In the banking industry, losing a customer is quite important and will undoubtedly impact the branch's turnover. 

## Project Overview

Create a dashboard for bank customer churn analysis that offers insightful data on maintaining customers and churn rates. This will help the bank make data-driven decisions to lower customer loss and raise overall customer satisfaction.

The goal of the problem statement is to identify the issues causing the loss of customers.

Due to its high loss of customers rates, the bank is trying to lower its customer acquisition expenses. It is essential to understand the causes of clients leaving in order to customize offerings and carry out focused retention campaigns. By doing so, the bank is able to better understand its customers' needs, improve its retention tactics, and pinpoint high-risk clients for targeted retention strategies.

## Data Cleaning/Preparation

- Load data into Power BI Desktop, dataset is a csv file.
- Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- checked for and removed any duplicates that were found.
- Deleting columns that are not related to customer attrition.
- Data type standardization.
- Dates should be arranged properly.
- Formatted numerical data for consistency.
- managing the text values and eliminating special characters from the name.
- Treated null values.

## Data Dictionary

- CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

  Credit score:

   - Excellent: 800–850

   - Very Good: 740–799

   - Good: 670–739

   - Fair: 580–669

   - Poor: 300–579

- Geography—a customer’s location can affect their decision to leave the bank.

- Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.

- Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

- Tenure—refers to the number of years that the customer has been a client of the bank. 

- Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

- NumOfProducts—refers to the number of products that a customer has purchased through the bank. 

- HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
     1 represents credit card holder
   	 0 represents non credit card holder
     
- IsActiveMember—active customers are less likely to leave the bank.
	    1 represents Active Member
	    0 represents Inactive Member
     
- Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

- Exited—whether or not the customer left the bank.
     0 represents Retain 
     1 represents Exit
- Bank DOJ — date when the Customer associated/joined  with the bank.


## Analysis

There are 10,000 total customers connected to the bank.

20% is the churn rate. In the banking industry, an annual churn rate of 5-7% is considered normal, and this is greater than the healthy range. 
Therefore, the bank needs to take the proper action and treat this as a severe issue.

The average tenure is five years, which shows how loyal customers are and how well the bank can keep them as clients. Within four to five years, the majority of the bank's clients leaves.

Given the fact that there are more male clients, the female churn rate is higher than the male one.

Churn Rate is highest in Germany.

Credit Card Holder Rate is 70.55%. Bank is doing good in this case. But, churn rate is also high in case of the credit card holders. People with fair and poor credit score are leaving the bank. 

Approximately 75,000 is the average balance per customer. Higher balance customers tend to churn more frequently, which bothers the bank because it affects its financial capital source.


## Recommendations:

- Improve customer service by addressing problems for customers and providing specific services to boost satisfaction.
  
- Reduce customer churn through setting up loyalty schemes and rewards for loyal consumers.
  
- Engage with clients on a regular basis across a variety of platforms, providing tailored offers and relevant updates.
 
- Gather consumer input, act upon it, and resolve issues to improve general satisfaction.
  
- Motivate customers to participate actively in banking activities, provide special bonuses, and tailor services according to their usage patterns.








