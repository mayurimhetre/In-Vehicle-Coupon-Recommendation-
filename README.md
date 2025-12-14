# In-Vehicle Coupon Recommendation

## Project Overview
The **In-Vehicle Coupon Recommendation** project focuses on predicting whether a driver will accept a coupon based on various contextual, customer, and situational factors. The dataset captures real-world driving scenarios and user preferences collected through a survey.

This is a **machine learning classification problem** where the goal is to determine coupon acceptance behavior.

---

## Problem Statement
The dataset was collected via a survey conducted on **Amazon Mechanical Turk**. Each survey instance represents a driving scenario, including information such as:
- Destination
- Current time
- Weather conditions
- Passenger details

Based on these factors, the survey records whether the driver accepted the coupon.

---

## Objective
To build a **classification model** that predicts whether a coupon will be accepted (`Yes` or `No`) under different driving scenarios using customer and situational features.

---

## Dataset Information

- **Dataset Name:** In-Vehicle Coupon Recommendation  
- **Source:** UCI Machine Learning Repository  
- **Dataset Type:** Multivariate  
- **Subject Area:** Business  
- **Associated Task:** Classification  
- **Feature Types:** Categorical, Integer  
- **Number of Instances:** 12,684  
- **Number of Features:** 25  
- **Missing Values:** Yes  
- **Currency:** USD ($)

---

## Target Variable

- **Y**
  - `1` → Coupon Accepted  
  - `0` → Coupon Not Accepted  

---

## Machine Learning Task
This project treats coupon acceptance as a **binary classification problem**, where the model learns patterns from customer demographics and situational contexts to predict user behavior.

---

## References
- **Dataset:** In-Vehicle Coupon Recommendation  
- **Repository:** UCI Machine Learning Repository  
- **DOI:** https://doi.org/10.24432/C5GS4P

---

## Notes
- Data preprocessing is required due to missing values.
- Most features are categorical and require appropriate encoding techniques.
- The project is suitable for experimenting with classification models such as Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.

---

## Author
Machine Learning Project – In-Vehicle Coupon Recommendation
