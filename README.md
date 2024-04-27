# Adventure-Works-dashboard

## Overview 

This report is for Adventure Works Cycles, a fictional retail company which sells bikes, bike components and accessories as well as cycling clothing. My mission was to provide insights based on their commercial activity from 01 January 2016 until 31 December 2017. 
As an observation, as this was my first project, I intentionally left the dashboard almost as it was originally done in March 2023 (exept some charts which needed to be changed as they were only there to practice my knowledge) in order to reflect my progress.


## Data set

The raw data came in form of 10 CSV files which were then transformed and cleaned in Power BI. No data dictionary was provided nor created by myself as data is self explenatory through its column titles. Besides these tables, there is another table with only one column with values used in price adjustment slicer.

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

 The aforementioned information has been put into context visually based on: <br>
  
  * **product characteristics:** product category, subcategory, color
  * **customer information:** full name, age group, income level, occupation, yearly income
  
### Key insights:

#### By product category and subcategory: 

  Bikes are the products which generate most sales, almost 95% of sales from the entire period came from the forementioned products. The main product subcategories sold were:
  
  * Road Bikes - 45.30% of total revenue generated from **all products** with the following product models generating most sales for this product subcategory: 
      * Road-250 (37% of total Road Bikes gross sales)
      * Road 150 (26% of total Road Bikes gross sales)
      * Road-350 (14% of total Road Bikes gross sales)
      * Road-550 (12% of total Road Bikes gross sales)
      
  * Montain Bikes - 34.45% of total revenue generated **all products** with the following product models generating most sales for this product subcategory:
      * Mountain-200 (84% of total Montain Bikes gross sales)
      * Mountain-100 (9% of total Mountain Bikes gross sales)

#### By customer:

 * 96% of our customers are 45 years old or older.   
 * **28% of our customers between 45 and 60 years old have no children**. The extra budged due to no children could explain the high spending of this category: **6.7 M USD** out of 25M USD overall revenue generated, more than all other customers between 45 and 60 with children combined.
* Although top 100 customers are from Oceania and Europe, United States has by far the highest number of customers: 7.2K or **42% of total customers** from the entire world with **7.9M USD** total revenue generated, followed by Australia with **3.4K customers** and with **7.4M USD** in revenues.

## Requirements

To use this PowerBI dashboard, you will need:

- Microsoft PowerBI Desktop installed on your computer.
- Access to data source from PowerBI service containing relevant data.
- Basic understanding of PowerBI to navigate and interact with the dashboard.

## Feedback and Support

Feedback on the dashboard is welcome and encouraged. If you encounter any issues or have suggestions for improvement, feel free to contact me through Linkedin.