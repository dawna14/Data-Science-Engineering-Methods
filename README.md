# Data-Science-Engineering-Methods
Assignments and Projects


# Assignment 2
The goal of this exercise is to build a dataset with features that can be used to analyze hiring trends in Fintech in the 24 largest banks by market cap in the United States.

1. Build a list of 100 keywords in Fintech and assign Fintech categories to each keyword - ## fintech_keywords.csv
2. Tag if a job is a fintech related job or not - data_mapping.py
3. Assign the categories as features to each job posting if it is a fintech related job - data_mapping.py
4. Analyze the final dataset and document insights. - actionable_insights.py

## PART 1 DATA PREP AND PRE-PROCESSING
Gathered and formed a single dataset of 100 fintech keywords

## PART 2 FORMED CLUSTERS(Categories) FOR DIFFERENT AREAS IN FINTECH - fintech_keywords.csv
• Summarize a single list of 100 keywords by manually reviewing the words/bigrams/trigrams
• Build a word cloud.
• Choose 8 clusters that these words could be bucketed into.

## PART 3 FEATURE ENGINEERING - data_mapping.py
• classified each job in the top 24 banks into one or more clusters
• determine which fintech words in these clusters are identified in the job descriptrion
• Calculated the number of occurrences of each keyword
• Determine if the job is related to fintech or not

## PART 4 ANALYZING THE DATA AND GAINING INSIGHTS
• Drawn actionable insights on the findings to answer the questions
o How are the top 24 banks hiring?
o How are the fintech related job hiring trends?
o Which companies have the most fintech related jobs and which ones least?
o Rank the jobs in fintech categories. Which categories have the most jobs and which ones least?
o If you have a job seeker, which areas would you recommend the job seeker to focus on based on available jobs?

## PART 5 BUILT A PIPELINE AND AUTOMATED THE PROCESS
• Built the pipeline in Airflow
• Dockerized the pipeline and tested it.
• Publish the Docker image to Dockerhub

# Assignment 3

This Project is based on Prediction of Interest Rates of Loans from the Lending Club Loan Data.
Please note that the prediction is focused on the borrowers with bad credit history.
Steps to Regenerate the Project:
1.    Clone the Project into any directory of your choice
2.    Download the Data from https://www.kaggle.com/wendykan/lending-club-loan-data and rename it to “loan.csv”
3.    Make sure that “loan.csv”, “EDA.ipynb”, and “DataCleaningAndModeling.ipynb” exists in the same folder
4.    Examining, analyzing and understanding the data using Exploratory Data Analysis in the file “EDA.ipynb”
5.    Data Cleaning and Preprocessing, Feature Engineering, Random Forest and Linear Regression Model for interest rate prediction exists in the file “DataCleaningAndModeling.ipynb”
