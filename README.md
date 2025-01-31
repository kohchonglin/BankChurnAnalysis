## Table of Contents
- [Project Problem Statement](#project-problem-statement)
- [About Data](#about-data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights and Recommendations](#key-insights-and-recommendations)

### Project Problem Statement
The bank seeks to better understand its customer churn rate, which impacts revenue and long-term growth. To address this, we are tasked to analyse the customer data to uncover the key factors contributing to churn and provide actionable recommendations to improve customer retention.


### About Data
Dataset retrieved from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data).

Data cleaning is performed using Excel before importing into Tableau.

### Exploratory Data Analysis
![ChurnRateGeography](https://github.com/user-attachments/assets/2d766858-481b-4134-87a0-c2995d7f6f84)  
An initial EDA showed that the churn rate for customers in Germany is 32.44%, while it stands at 16.15% in France and 16.67% in Spain.  

![Dashboard_ChurnRate](https://github.com/user-attachments/assets/07b2d28b-8eb0-41d0-9050-9165d527fc51)  
[Click here to view dashboard ](https://public.tableau.com/app/profile/chong.lin.koh/viz/Capstone_BankChurn_17375325867250/ChurnrateOverviewDashboard
)    
A dashboard was created using Tableau to analyze churn rate across different variables, segmented by geography.  
Several areas have been highlighted as contributing to the high churn rate and presenting irregular patterns.  

### Key Insights and Recommendations

1. Churn rate is high for customers in the Balance range of 100,000 – 150,000 across all Salary range in Germany. The rate is significantly higher among customers who are not active.   
![GermanyBalanceSalaryChurnRate](https://github.com/user-attachments/assets/f78f3cd7-7ddb-4815-b172-942186c5c485)  
**Recommendation:** Offer promotions/incentives to encourage active transactions targeted at customers with balance range between 100,000 – 150,000



2. Consistently high churn rates observed across all tenure durations in Germany. Rises and peaks in Year 1 at 39.77%, contrasting with the downward trend observed in France and Spain.  
![GermanyHighChurnRateTenure](https://github.com/user-attachments/assets/717168a8-501a-497f-87d9-cbb7f425593a)  
Germany has the highest average balance across all tenure durations.  
![GermanyAvgBalanceTenure](https://github.com/user-attachments/assets/36cf4caf-009d-4db2-aa13-d8dbf3f6e893)  
**Recommendation:** Focus efforts on Germany, where customers show high average balances yet experience high churn. Implement a loyalty program focused on the first few years to improve customer retention. 

3. Churn rate is at 100% for customers with 4 products and 82.41% for those with 3 products across France, Germany and Spain. 
Among customers who own 3 or 4 products, those with a Fair credit score make up the largest group, followed by Good, Poor, Very Good and Excellent.  
![ProductsCreditScore](https://github.com/user-attachments/assets/71adf761-efd3-4856-88b0-736c476b54e7)
**Recommendation:** Evaluate the risk levels of the offered products and ensure they are tailored to match the customer’s financial profile and requirements.







