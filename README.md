# Employee-Turnover-prediction-
# TalentCore Employee Turnover Predictor

An intelligent employee attrition prediction system for **TalentCore Pvt. Ltd.**, powered by Machine Learning. The system predicts whether an employee is likely to leave the company — helping HR teams take proactive steps to retain skilled talent.

## Problem

TalentCore Pvt. Ltd. has been facing a rising number of employee resignations, leading to increased recruitment costs, project delays, and loss of skilled talent. The HR department needs a data-driven way to identify at-risk employees before they resign.

## Solution

A **Logistic Regression** classification model (with L1 & L2 regularization) trained on employee data. Given an employee's profile, the model predicts:

- `1` → Employee likely to leave
- `0` → Employee likely to stay

## Objectives

1. Build a baseline Logistic Regression model
2. Improve it using Regularization (L1 & L2)
3. Compare model performances and recommend the best approach

## Dataset

900 rows × 15 features representing various employee metrics:

| Feature | Description |
|---|---|
| `Job_Satisfaction` | Level of satisfaction with the job |
| `Performance_Rating` | Employee performance score |
| `Years_At_Company` | Number of years worked at the company |
| `Work_Life_Balance` | Balance between work and personal life |
| `Distance_From_Home` | Distance of home from workplace |
| `Monthly_Income` | Monthly salary |
| `Education_Level` | Education qualification level |
| `Age` | Age of employee |
| `Num_Companies_Worked` | Number of previous companies worked at |
| `Employee_Role` | Encoded job role |
| `Annual_Bonus` | Annual bonus received |
| `Training_Hours` | Training hours attended |
| `Department` | Encoded department |
| `Annual_Bonus_Squared` | Engineered feature (bonus²) |
| `Annual_Bonus_Training_Hours_Interaction` | Interaction feature between annual bonus and training hours |
| `Employee_Turnover` | **Target** — 1 = Left, 0 = Stayed |

## Project Structure