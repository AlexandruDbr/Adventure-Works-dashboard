# Adventure-Works-dashboard

## Overview 

This report is for Adventure Works Cycles, a fictional retail company which sells bikes, bike components and accessories as well as cycling clothing. My mission was to provide insights based on their commercial activity from 01 January 2016 until 31 December 2017. 
As an observation, as this was my first project, I intentionally left the dashboard almost as it was originally done in March 2023 (exept some charts which needed to be changed as they were only there to practice my knowledge) in order to reflect my progress.


## Data set

The raw data came in form of 10 CSV files which were then transformed and cleaned in Power BI. No data dictionary was provided nor created by myself as data is self explenatory through its column titles. "Price Adjustment(%)" is a virtual 1 column table create for the "price adjustment" slicer.

The cleaning process for this data set was generally straightforward, requiring mainly header promotion, data type checking and corrections as well as basic creation of additional columns, such as: calculating the age of each customer based on their birthday, custom column to add each customer in an age group, adding month number, year, quarter end, end of month, etc. 

## Analysis starting point and insights:

### Analysis starting point

The analysis has been focused on the following financial and commercial information:
 * gross revenue
 * cost of goods sold
 * gross profit
 * number of orders generated
 * number of returns registered
 * customer spendings and orders

 The aforementioned information has been visualised based on: <br>
  * **product characteristics:** product category, subcategory, color
  * **customer information:** full name, age group, income level, occupation, yearly income
  

### Key insights by points of interest:

#### By product category and subcategory: 
  Bikes are the products which generated most sales, almost 95% of sales from the entire period came from this product category (check Treemap from "Exec Summary" tab). The most popular product subcategories of Bikes category as well on the global level were:
  
  * Road Bikes - 45.30% of total revenue generated from **all products**. The following models generated most sales for this product subcategory: 
      * Road-250 (37% of total Road Bikes gross sales)
      * Road 150 (26% of total Road Bikes gross sales)
      * Road-350 (14% of total Road Bikes gross sales)
      * Road-550 (12% of total Road Bikes gross sales)
      
  * Montain Bikes - 34.45% of total revenue generated **all products**. The following models generated most sales for this product subcategory:
      * Mountain-200 (84% of total Montain Bikes gross sales)
      * Mountain-100 (9% of total Mountain Bikes gross sales)


#### By customer:
 * 96% of our customers are 46 years old or older.
 * **28% of our customers have no children**. The extra budged as result to no children could explain why this category has the highest spending: **7.36 M USD** out of approximately 25M USD from all categories combined, more with 25% than customers with 1 child and 33% more than customers with 2 children. Moreover, as the number of children in the household increases, the turnover decreases, indicating that either our products are not well suited for children in terms of size, or that our product portfolio is notorious amongst people between 46 and 60.
* Although top 100 indivual customers are from Pacific and Europe, United States has by far the highest customer base: 8.7K (**50% of total customers**) with **9.7M USD** revenue generated, around 1/3 of the revenue generated by Advanture Works on the whole.

## Requirements

To use this PowerBI dashboard, you will need:

- Microsoft PowerBI Desktop installed on your computer.
- Access to data source from GitHub or PowerBI service containing relevant data.
- Basic understanding of PowerBI to navigate and interact with the dashboard.

## Feedback and Support

Feedback on the dashboard is welcome and encouraged. If you encounter any issues or have suggestions for improvement, feel free to contact me via Linkedin.