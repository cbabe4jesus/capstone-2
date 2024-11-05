# capstone-2

### Project Title: Customer Segmentation for a Subscription Service

### Project Overview
The aim of this project is to analyze customer data for a subscription service to identify 
segments and trends. To gather enough information through the data recieved. 
To know the best performance from our data, understand customer behavior,
track subscription types and identify key trends in cancellations and renewals. 

### Data Sources
The primary source of data used here is CustomerData.csv this is a closed source data 

### Tools Used
- Microsoft Excel for data cleaning, analysis and visualization.
- SQL - Structured Query Language for quering of data.
- PowerBI for data anaiysis and visitualization.
- GitHub for portfolio building.


### Data Cleaning and preparations
In the initial phase of the data cleaning and preparations, we perrform the following actions;
1. Uploading of data and inspection
2. Handling missing variables
3. Data cleaning and formatting

### Exploratory Data Anaysis
This involved data exploration to give insights and answers to some questions about the data such as;
- Identify the most popular subscription types
- To find subscription patterns
- To find average subscription duration for all customers. e.t.c.

### Data Analysis
This is where we include some basic lines of codes or queries or even some of the DAX expression ussed during the analysis;

~~~SQL
 SELECT Region, Count (*)AS Customers
   FROM [CAPSTONE_DB].[dbo].[capstone 1]
  Group by Region;
~~~
   
