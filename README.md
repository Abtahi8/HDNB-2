Task 2
Overview
In this assessment, you will analyze the Titanic dataset using SQL in BigQuery and create visualizations to answer specific questions. The assessment is designed for those who are new to SQL and should be completed within 3-4 hours.


Dataset
You will use the Titanic Dataset from Kaggle. Focus on the **train.csv** file, which contains essential data on passengers, including survival status, age, gender, and class.

Key Fields
:PassengerId: Unique ID for each passenger.
Survived: 0 = Did not survive, 1 = Survived.
Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
Name: Passenger's name.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings and spouses aboard.
Parch: Number of parents and children aboard.
Ticket: Ticket number.
Fare: Fare paid for the ticket.
Cabin: Cabin number (if known).
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Tasks

1. Data Preparation:
Import Data into BigQuery:
 
Create a new BigQuery project or use an existing one.
 
Upload the **train.csv** dataset.
Data Cleaning:
 
Handle any missing values in the Age, Fare, and Embarked columns.
 
Ensure data types are correct (e.g., Pclass, Survived should be integers, Fare and Age should be numeric).
2. Data Analysis
Answer the following questions using SQL queries in BigQuery:

Questions:
1. Overall Survival Rate:
 
 What percentage of passengers survived?
2. Survival by Passenger Class (Pclass):
 
 What is the survival rate for each passenger class (1st, 2nd, 3rd)?
3. Survival by Gender (Sex):
 
 What is the survival rate based on gender?
4. Fare vs. Survival:
 
 What is the average fare for survivors vs. non-survivors?
5. Age vs. Survival:
 
 What is the average age of survivors and non-survivors?
6. Survival by Embarkation Port (Embarked):
 
 What is the survival rate based on the port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)?
7. Family Size vs. Survival (SibSp and Parch):
 
 How does family size (sum of SibSp and Parch) affect survival?
8. Top 10 Survivors by Fare Paid:
 
 Who are the top 10 passengers who paid the highest fare and survived?
3. Dashboard Creation
After answering the questions through your SQL analysis, create a dashboard based on **your own insights** from the data. You can use any visualization tool (e.g., Google Data Studio, Tableau, Power BI, or Excel) to create your dashboard.
Suggested Visuals: You can visualize data like survival rates, survival by gender, class, and fare, or any other insights you found compelling. However, the design and focus of the dashboard are up to you.
Customization: Feel free to explore beyond the given questions, find other trends in the dataset, and reflect them in your dashboard.
4. Submission
SQL Queries: Submit a document with the SQL queries used to answer the questions.
Dashboard or Visualizations: Submit screenshots or a link to the dashboard.
Evaluation Criteria
Correctness of SQL Queries
Clarity and Creativity of the Dashboard
Insights Derived from Data 

