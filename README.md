  # Customer Churn Analysis

 ## Table Of Content

    - [Project Overview](#project-overview)
    - [Data Source](#data-source)
    - [Tools](#tools)
    - [Data Collection/Preparation](#data-collection/preparation
    - [Data Modeling](#data-modeling)
    - [Key Finding](#key-finding)
    - [Recommendation](#recommendation)

 ### Project Overview

     This project aims to provide insights into the churn rate of customers,by analyzing various aspect of the Churn data we seek to identify trends,make data-driven recommendation , gain deeper understanding of the customer churn rate.
     Churn refers to the loss of customers who stop using a company's product or service over a specific period.
     Churn analysis is usually conducted to understand the factors contributing to customer churn and develop strategies to reduce churn rate. This analysis typically involves examining historical customer data, identifying patterns, and building models to predict churn risk.

 ### Data Source
  
     Customer data: The dataset used for this analysis is the "Bank Customer Churn Prediction.csv" file, containing detailed information about each customer data.

 ### Tools

     - Excel - Data cleaning 
     - Power bi - Creating report
     - Power query editor - Transform data


 ### Data Collection/ Preparation 
 
     The data source was connected using Text/csv data connector
     In the data preparation; Clean and transform raw data
     the following task was performed:
     - Removing unwanted columns
     - Renamed columns
     - Replacing values


 ### Data Modeling 

     Queries were created to organise data for analysis and reporting 
     Measure were created using DAX
     ...Customer = count('customer data'[customer ID])
        Customer Lost = CALCULATE(COUNT('customer data'[churn status])
     ...


 ### Key Finding 

     The highest churn rate is among inactive customers. This suggests that the bank needs to focus on engaging with inactive customers and providing them with incentives to continue using the bank's services.
     Customers with a credit score of less than or equal to 400 have the highest churn rate. This indicates that the bank needs to focus on providing better services to customers with lower credit scores and ensuring that they are satisfied with the bank's offerings.


 ### Recommendation