# AI-Powered-personal-Finance-Advisor
This project is an AI-powered personal finance advisor that helps users analyze their spending habits, forecast future expenses, and receive personalized financial recommendations. It combines exploratory data analysis, machine learning, and intelligent insights to guide smarter budgeting decisions.

1) Project Goals :-
A. Understand user spending behavior through data visualization and pattern analysis.
B. Build a predictive model that estimates future spending based on past data.
C. Generate personalized financial advice to help users save more and spend wisely.
D. Deploy the project as an interactive AI finance advisor tool.

2) Datasets :-
The dataset consists of three CSV files (sourced from Kaggle):
A. 11 march 2025.csv
B. budget_data.csv
C. budjet (2).csv
Each file contains transactions with three key columns:
~date – Timestamp of the transaction
~category – Type of expense (e.g., Restaurant, Market, Coffee)
~amount – Money spent on that transaction
~All three datasets were merged and cleaned to create a single file named cleaned_budget_data.csv. 

3) Data Cleaning :-
~Merged all CSV files into one dataset
~Converted date to datetime format
~Fixed category typos (e.g., “Coffe” → “Coffee”)
~Removed duplicates and missing values
~Converted amount column to numeric

4) Exploratory Data Analysis (EDA) :-
--Key insights were generated using Python libraries like pandas, matplotlib, and seaborn.
--Visual analyses include:
~Daily Spending Trend – How spending changes over time
~Spending by Category – Which expense categories dominate
~Monthly and Weekly Patterns – When users spend the most money
~Category Frequency – Which types of purchases are most common

--Key Findings:
~Identifies your top spending categories
~Detects peak spending days and months
~Calculates your average daily spending

5) Machine Learning Model :-
--A Random Forest Regressor was trained to predict spending amounts based on:
~Date features (year, month, weekday)
~Encoded expense categories
~Model Evaluation:

--Metrics used:
~Mean Absolute Error (MAE)
~Mean Squared Error (MSE)
~R² Score
--These metrics helped me to evaluate the model’s accuracy in predicting the user spending behavior.

6) AI-Generated Financial Advice :-
--After training, the AI advisor:
~Estimates your future weekly spending
~Identifies your most expensive categories
~Suggests savings goals and expense control tips
~Provides personalized, data-driven recommendations
--Example advice:
“Your average daily spending is $540. Try setting a target 10% below this to save more.”
“You tend to spend the most on ‘Restaurant’. Consider reducing frequency or setting a weekly limit.”

7) Future Improvements :-
~Build a Streamlit or Flask web app for interactive predictions
~Add income data to suggest savings ratios
~Implement AI-based anomaly detection for unusual expenses
~Connect with real bank or expense-tracking APIs

  8) Author :-

  Jayastu Adkar
  
  Data Science Student | Finance Enthusiast |
  Building data-driven financial intelligence solutions. 
