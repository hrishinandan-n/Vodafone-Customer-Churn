# Vodafone-Customer-Churn

## Problem Statement

- Customer churn is a major concern for telecom providers, as acquiring new customers is significantly more expensive than retaining existing ones.  
- This project aims to build and evaluate machine learning models that can accurately predict whether a customer will churn based on demographic, service usage, and billing-related features.

## Dataset Overview

- Each row represents an individual telecom customer.
- The target variable indicates whether a customer has churned.
- The goal is to build a classification model to predict customer churn.

### Features

- `customerID`: Unique identifier for each customer.
- `gender`: Gender of the customer.
- `SeniorCitizen`: Indicates whether the customer is a senior citizen.
- `Dependents`: Whether the customer has dependents.
- `tenure`: Number of months the customer has been with the company.
- `PhoneService`: Indicates whether the customer has phone service.
- `MultipleLines`: Whether the customer has multiple phone lines.
- `InternetService`: Type of internet service subscribed.
- `OnlineSecurity`: Whether online security service is enabled.
- `OnlineBackup`: Indicates if online backup service is subscribed.
- `DeviceProtection`: Whether device protection is included.
- `TechSupport`: Availability of technical support.
- `StreamingTV`: Whether TV streaming services are subscribed.
- `StreamingMovies`: Whether movie streaming services are subscribed.
- `Contract`: Type of customer contract.
- `PaperlessBilling`: Indicates use of paperless billing.
- `PaymentMethod`: Method used for bill payment.
- `MonthlyCharges`: Monthly amount charged to the customer.
- `TotalCharges`: Total charges accumulated over the customer’s tenure.
- `numAdminTickets`: Number of administrative support tickets raised.
- `numTechTickets`: Number of technical support tickets raised.
- `Location`: Geographic location of the customer.

**Target**
- `Churn`: Indicates whether the customer has churned (1 = Yes, 0 = No).
