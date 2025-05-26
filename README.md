Data Analysis: 

Sales Data Insights 

Objective 

Analyze a given CSV file (sales_data.csv) using Pandas and NumPy only. 
This file contains data about products, their categories, quantities sold, unit prices, and total revenue. 

Dataset Information 

You are provided with a file called sales_data.csv. It includes the following columns: 

• Product ID 

• Product Name 

• Category 

• Quantity Sold 

• Unit Price 

• Total Revenue 

Analysis Tasks 

Perform each of the following steps. Document your code and output clearly: 

1. Load the CSV file using Pandas.
3. Display the first 5 records using .head().
5. Show a summary of the dataset using .describe() and .info(). 
6. List all unique product categories. 
7. Calculate the total and average revenue using Pandas and NumPy. 
8. Identify the product with the highest total revenue. 
9. Find the product with the highest quantity sold. 
10. Group the data by Category and calculate the average revenue per category. 
11. Count how many products belong to each category. 
12. Create a new column called Performance: 
    o If Total Revenue > 50,000, mark as "High". 
    o Else mark as "Low". 
13. Count how many products are labeled as "High" and how many as "Low" in the Performance column.
