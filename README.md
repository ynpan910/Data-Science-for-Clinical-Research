#-----------------------------------
Homework 3: SQL Assignment

1. Use SQL queries to finish this patient demographics table. Fill in all cells in the table under
the “Descriptive statistics” and “Percentage of the cohort” columns. Provide your SQL queries
under the table.

2. Find all the medications that at least 100 patients were exposed to, order by the number of
patients taking the medication in a descending order. Your query results should contain the
following information: “drug_concept_id, drug_name, and number of patients taking the drug”.
Provide your SQL queries and results in below. (Note: please use the drug exposure table for
medications)

3. Find all the diagnoses (concept_id, and name) that have at least 500 patients. Your query
results should contain the following information: “disease_concept_id, disease_name, and
number of patients have this disease”, Provide your SQL queries and results in below. (Note:
please use the condition_occurrence for diagnoses)


#-----------------------------------
Homework 4: Pandas Assignment
In this assignment, you'll be working with a dataset designed to help you analyze and understand patterns in fraudulent activity. You will be using a CSV file titled fraud_final_dataset.csv, which contains various features related to purchases and user data. Your task is to perform basic data manipulation, exploratory analysis, and derive insights that could potentially aid in identifying fraudulent behavior.

Here’s a breakdown of the tasks you'll complete:

Understanding the Dataset Structure:

Load the dataset and check its dimensions by determining how many columns and rows are present in the data.
Basic Data Analysis:

Calculate the average (mean) age of the users in the dataset.
Find the maximum and minimum purchase values to understand the range of transaction amounts.
Creating a New Feature for Browser Categorization:

The dataset contains a column that tracks the browser used by the users (Chrome, IE, Safari, FireFox, and Opera). You will create a new column, browser_combined, that categorizes the browsers into three groups:
Chrome and IE as "Browser 1"
Safari and FireFox as "Browser 2"
Opera as "Opera"
Filtering Data:

Select records where the purchase value is greater than 20 for further analysis.
Comparing Age Statistics for Class Labels:

For the filtered data, you will compute the mean, maximum, and minimum age, separately for the two different classes (0 and 1). This will help identify if there are any age-related patterns in the fraudulent vs. non-fraudulent transactions.


