
# Titanic Data Analysis with SQL in BigQuery

This project is a beginner-friendly data analysis of the **Titanic dataset**, conducted using **SQL in Google BigQuery** and visualized through a customizable dashboard. The objective is to uncover survival patterns based on factors such as passenger class, gender, age, fare, and port of embarkation.

## Project Overview

The Titanic dataset, originally from [Kaggle](https://www.kaggle.com/competitions/titanic/data), contains demographic and travel information of passengers aboard the RMS Titanic. Using SQL, we answer key analytical questions and draw insights into who was more likely to survive the tragedy.

The final output includes:
- Cleaned and structured dataset in BigQuery
- A set of analytical SQL queries answering specific business questions
- A visual dashboard summarizing findings

---

## Data Source

Passenger Data: [CSV file](https://github.com/Abtahi8/HDNB-2/blob/main/Titanic%20passenger.csv)
## Dataset Description

We used `train.csv` from the Titanic dataset, which contains the following key fields:

| Column       | Description                                           |
|--------------|-------------------------------------------------------|
| PassengerId  | Unique ID for each passenger                          |
| Survived     | Survival (0 = No, 1 = Yes)                            |
| Pclass       | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)              |
| Name         | Name of the passenger                                 |
| Sex          | Gender                                                |
| Age          | Age in years                                          |
| SibSp        | # of siblings/spouses aboard                          |
| Parch        | # of parents/children aboard                          |
| Ticket       | Ticket number                                         |
| Fare         | Passenger fare                                        |
| Cabin        | Cabin number (if available)                           |
| Embarked     | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## Tasks Completed

### 1. Data Preparation
- Uploaded `train.csv` into Google BigQuery
- Handled missing values (`Age`, `Fare`, `Embarked`)
- Ensured proper data types (e.g., integers for `Pclass`, `Survived`)

### 2. Data Analysis (SQL in BigQuery)
We answered the following questions:
1. What percentage of passengers survived?
2. What is the survival rate by passenger class?
3. What is the survival rate by gender?
4. What is the average fare for survivors vs. non-survivors?
5. What is the average age of survivors and non-survivors?
6. What is the survival rate by port of embarkation?
7. How does family size (SibSp + Parch) affect survival?
8. Who are the top 10 fare-paying survivors?

### 3. Dashboard Creation
- Created a visual dashboard using Lookerstudio
- Included survival breakdowns by gender, class, fare, and embarkation port
- Custom visualizations to communicate insights clearly

---

## Dashboard
[Dashboard Link]([https://github.com/Abtahi8/HDNB-2/blob/main/HDNB_Final_Task.pdf](https://lookerstudio.google.com/reporting/f7f98975-6484-42ea-9f72-26b94f956b13/page/IQrPE/edit?s=kqenz5Xaxdk))

---

## Key Insights

- Average survival rate was 38.38%
- Females had a significantly higher survival rate.
- 1st-class passengers had the highest survivor percentage and surprisingly 3rd-class passenfers had higher survivors than 2nd-class passengers.
- Higher fare correlated with higher survival likelihood.
- Ages ranging from 20-40 had better survival rate and passengers aged around 30 having the highest survivor count.

---




 

