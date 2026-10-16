# Netflix Customer Churn Analysis

## Project Overview

This project analyses customer churn in a Netflix subscription dataset containing 5,000 customers. The objective is to identify patterns associated with customer cancellations and develop evidence-based recommendations that could help improve customer retention.

## Business Problem

Customer churn can affect subscription revenue and long-term business performance. Understanding how churn varies across subscription types, customer engagement, age groups, devices, and payment methods can help a business identify areas that require further investigation.

## Project Objectives

- Calculate the overall customer churn rate.
- Compare churn rates across subscription types.
- Investigate churn patterns across age groups.
- Examine the relationship between login inactivity, viewing activity, and churn.
- Compare profile usage, devices, and payment methods.
- Develop evidence-based business recommendations.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Anaconda

## Dataset

The dataset contains customer information, including:

- Customer ID, age, and gender
- Subscription type and monthly fee
- Watch hours and average daily watch time
- Days since last login
- Device and payment method
- Number of profiles
- Churn status
- Favourite genre and region

## Key Findings

### 1. Subscription Type

The Basic subscription recorded a churn rate of 61.83%, compared with 45.44% for Standard and 43.71% for Premium. Premium had the lowest churn rate despite having the highest monthly fee among the three plans.

### 2. Age Groups

Customers aged 35–44 had the lowest observed age-group churn rate at 48.56%. Customers aged 45–54 had the highest at 53.97%.

### 3. Login Inactivity

Customers inactive for 31–60 days had an observed churn rate of 75.09%, compared with 13.38% for customers who had logged in within the previous 7 days.

### 4. Customer Engagement and Profiles

The analysis compared viewing activity and profile usage between retained and churned customers. These measures may help identify patterns associated with retention.

### 5. Devices and Payment Methods

Churn rates differed across device and payment categories. These differences require further investigation before attributing them to technical issues, payment difficulties, or affordability.

### 6. Customer Age

The average age in the dataset was approximately 43 years.

## Business Recommendations

1. Investigate why Basic subscribers have a higher churn rate than Standard and Premium subscribers.
2. Test customer re-engagement strategies for customers showing prolonged login inactivity or declining viewing activity.
3. Investigate profile usage within each subscription type.
4. Examine device categories with higher churn to identify potential usability or technical issues.
5. Investigate payment method differences, including payment success and customer characteristics.
6. Compare customer engagement patterns across age groups.
7. Monitor churn rates regularly and measure the results of retention initiatives.

## Limitations

This analysis identifies patterns and associations in the available dataset. It does not establish that the observed factors directly cause customer churn. Some potential explanations require additional customer feedback or further analysis.

## Conclusion

The project demonstrates how Python and data analysis can be used to investigate customer churn and translate findings into potential business actions. The results highlight subscription type and login inactivity as important areas for further investigation.

## Author

Data Analytics Portfolio Project
