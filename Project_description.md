## Objective of the project
The goal of the project is to have insight into the sales data of Walmart and gather the various factor that affect sales in different branches.

## Data description
The dataset was obtained from the Kaggle. This dataset contains sales transactions from a three different walmart branches, respectively located in Mandalay, Yangon and Naypyitaw. 
The data contains 17 columns and 995 records: Each columns with its description and data type provided in "Data_Descriptio.csv" file.

## Main Analysis parts
Product Analysis (EDA)
To findout the various product lines, best performing products lines and the product lines that need to be improved.

Sales Analysis
To answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what improvements are needed to gain more sales.

Customer Analysis
To unpack the different customers segments, purchase trends and the profitability of each customer segment.

## Used Approach
Data Wrangling/Preparation: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
                            In this case the data is more or less clean. Becouse when creating the table, I set NOT NULL for each field, therefore null values are filtered out.

## Build a database
Create table and insert the data.

## Feature Engineering: 
To generate some new columns from existing ones.
Add a new column- named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
                - named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
                - named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

## Business Questions To Answer
Generic/General Question
How many unique cities does the data have?
In which city is each branch?

## Product
How many unique product lines does the data have?
What is the most common payment method?
What is the most selling product line?
What is the total revenue by month?
What month had the largest COGS?
What product line had the largest revenue?
What is the city with the largest revenue?
What product line had the largest VAT?
Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
Which branch sold more products than average product sold?
What is the most common product line by gender?
What is the average rating of each product line?

## Sales
Number of sales made in each time of the day per weekday
Which of the customer types brings the most revenue?
Which city has the largest tax percent/ VAT (Value Added Tax)?
Which customer type pays the most in VAT?

## Customer
How many unique customer types does the data have?
How many unique payment methods does the data have?
What is the most common customer type?
Which customer type buys the most?
What is the gender of most of the customers?
What is the gender distribution per branch?
Which time of the day do customers give most ratings?
Which time of the day do customers give most ratings per branch?
Which day fo the week has the best avg ratings?
Which day of the week has the best average ratings per branch?



