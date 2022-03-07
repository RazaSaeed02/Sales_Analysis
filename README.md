# Sales_Analysis

An analysis of 12 months worth of sales data for an electronics store. The analysis aimed to answer the following 5 questions:

1. What was the best month for sales? How much was earned that month?
2. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
3. What city sold the most product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

### Breakdown

#### Data Preparation
- Concatenated monthly csv files into one csv file for the entire year

#### Data Cleaning
- Dropped any rows where all the values in that row were missing
- Converted "Order Date" column to a datetime datatype
- Converted "Quantity Ordered" and "Price Each" columns to numeric datatypes

#### Data Engineering
A few examples:
- Created a new column "Month" by extracting the month from the Order Date column
- Created a new column "Location" by extracting the City and State from the "Purchase Address" column

#### Data Visualization
- Used the matplotlib library to plot bar charts and line charts to visualize the answers to the questions.

