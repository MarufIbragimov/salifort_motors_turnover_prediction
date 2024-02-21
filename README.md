# salifort_motors_turnover_prediction  

This is a capstone project from Google Advanced Data Analytics Professional Certificate.

## Objective  
The objective is to analyze employee data from a fictional company 'Salifort Motors'. The goal is to identify the key factors influencing employee turnover and build a turnover prediction model.  

## Data Dictionary  
This project uses a dataset called HR_capstone_dataset.csv. It represents 10 columns of self-reported information from employees of a multinational vehicle manufacturing corporation. 

The dataset contains:

  14,999 rows – each row is a different employee’s self-reported information

  10 columns

| Column name           | Type  | Description                                                        |
|-----------------------|-------|--------------------------------------------------------------------|
| satisfaction_level    | int64 | The employee’s self-reported satisfaction level [0-1]              |
| last_evaluation       | int64 | Score of employee's last performance review [0–1]                  |
| number_project        | int64 | Number of projects employee contributes to                         |
| average_monthly_hours | int64 | Average number of hours employee worked per month                  |
| time_spend_company    | int64 | How long the employee has been with the company (years)            |
| work_accident         | int64 | Whether or not the employee experienced an accident while at work  |
| left                  | int64 | Whether or not the employee left the company                       |
| promotion_last_5years | int64 | Whether or not the employee was promoted in the last 5 years       |
| department            | str   | The employee's department                                          |
| salary                | str   | The employee's salary (low, medium, or high)                       |

## Methodology  
Given that the course didn't cover hyperparameter tuning for Logistic Regression, I seized this capstone project as an opportunity to become more familiar with the algorithm and its hyperparameters. Consequently I chose to use Logistic Regression as the sole method for creating the prediction model. While more advanced algorithms like Random Forest or XGBoost might yield superior results, mastering Logistic Regression remains essential due to its fundamental nature. Focusing exclusively on Logistic Regression also allowed me to better understand the intricacies of variable selection through data exploration and statistical analysis.
