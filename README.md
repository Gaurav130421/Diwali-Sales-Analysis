# diwali sales analysis using python

![Diwali Sales Logo](https://github.com/Gaurav130421/Diwali-Sales-Analysis/blob/main/Diwali%20sales%20logo.jpg)


Diwali Sales Analysis

Project Overview

This project analyzes Diwali sales data to uncover insights into customer purchasing behavior during the festive season. The analysis focuses on identifying key trends and patterns in sales based on demographic and product-related factors. Using Python and popular data analysis libraries, the project processes and visualizes the data to provide actionable insights.

Dataset

The dataset, Diwali Sales Data.csv, contains detailed information about sales transactions, including:





User_ID: Unique identifier for each customer



Cust_name: Customer name



Product_ID: Unique identifier for each product



Gender: Customer gender (M/F)



Age Group: Age range of the customer (e.g., 0-17, 18-25, 26-35, etc.)



Age: Specific age of the customer



Marital_Status: Marital status (0 for unmarried, 1 for married)



State: Customer's state of residence



Zone: Geographical zone of the state



Occupation: Customer's occupation



Product_Category: Category of the purchased product



Orders: Number of orders placed



Amount: Total purchase amount



Status and unnamed1: Unused columns (contain NaN values)

The dataset consists of 11,251 records and 15 columns.

Objectives

The primary goal of this project is to analyze Diwali sales data to identify:





Key customer demographics driving sales



Popular product categories



Regional sales trends



Top-selling products based on order volume

Tools and Libraries

The analysis is performed using the following Python libraries:





Pandas: For data manipulation and analysis



NumPy: For numerical operations



Matplotlib: For plotting and visualization



Seaborn: For enhanced data visualization



Jupyter Notebook: For interactive coding and visualization

Analysis Workflow





Environment Setup:





Installed required libraries, including seaborn, using pip.



Imported libraries: numpy, pandas, matplotlib.pyplot, and seaborn.



Configured Matplotlib for inline plotting.



Data Loading:





Loaded the dataset (Diwali Sales Data.csv) into a Pandas DataFrame using unicode_escape encoding to handle special characters.



Data Exploration:





Checked the dataset's shape (11,251 rows, 15 columns).



Inspected the first few rows to understand the structure and content.



Data Analysis and Visualization:





Grouped data by Product_ID to calculate the total number of orders.



Identified the top 10 products by order volume.



Visualized the results using a bar plot created with Seaborn.



Key Findings:





Demographics: Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are the most likely to make purchases.



Product Categories: The highest demand is for products in the Food, Clothing, and Electronics categories.
