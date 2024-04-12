## Proyect description
A telecommunications company is developing a new feature for supervisors to have information about the least effective operators.
We analyzed the company's data to conduct a comprehensive analysis to optimize its processes. Additionally, we created an efficiency classification system using machine learning tools that can serve as a reference for the company.

## Tasks
1. Describe the study objectives.
2. Study the tables.
3. Perform SQL queries for the following tasks:
   - Find the number of books published after January 1, 2000.
   - Identify the publisher that has published the highest number of books with more than 50 pages.
   - Identify the author with the highest average rating of books.
   - Find the average number of text reviews among users who rated more than 50 books.
4. Generate query results.
5. Describe conclusions for each task.

## Data Description

### First dataset (telecom_dataset_us.csv): Activity and Operator Information

- user_id: Customer account ID.
- date: Date statistics were retrieved.
- direction: Call direction ('out' for outgoing, 'in' for incoming).
- internal: Whether the call was internal (between a customer's operators).
- operation_id: Operator identifier.
- is_missed_call: Whether it was a missed call.
- calls_count: Number of calls.
- call_duration: Call duration (excluding waiting time).
- total_call_duration: Total call duration (including waiting time).

### Second dataset (telecom_clients_us.csv): Customer Information

- user_id: Customer account ID.
- tariff_plan: Current tariff plan of the customer.
- date_start: Customer registration date.

## Contents:

1. Initialization:
    - Data Description
    - Data Optimization

2. Exploratory Analysis:
    - Basic Information
    - Missing Values
    - Visualization of Statistics
    - Records by Date
    - Critical Variables
    - Outliers
    - Customer Information
    - Exploratory Analysis Conclusions

3. Preprocessing:
    - Duplicate Records
    - Missing Values
    - Data Type Correction
    - Outliers
    - Dataset Merge
    - Preprocessing Conclusions

4. Efficiency Analysis and Metrics:
    - Data Study and Verification
    - Efficiency Variable Study
    - Efficiency Metrics Construction
    - Hypothesis Testing
    - Classification Model Construction with ML

5. Conclusions and Recommendations

6. References and Others

## Used libraries
+ pandas
+ numpy
+ matplotlib
+ seaborn
+ plotly
+ random
+ scipy
+ sklearn
