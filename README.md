# Amazon-Case-Study-DSA-Data-Analysis-Project

### Project Title: Amazon Customer Review Analysis

### Project Overview
This Data Analysis project amims to generate insight into the customer review of an E-commerce project (Amazon). By analyzing the various parameters in the data received we seek to generate enough insights that can guide product improvement, marketing strategies, and customer engagement.

### Data Sources
The primary source of Data used here is Amazon case study from the Data Analysis Capstone Project 

### Tools Used
- Microsoft excel for: 
   1. Data cleaning
   2. Data Analysis
   3. Data Visualization
- GitHub for portfolio building

### Data Cleaning and Preparations
  1. Data loading and Inspection
  2. Handling missing variables
  3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved the exploring of the Data to answer some questions about the Data such as;
- What is the average discount percentage by product category?
- How many products are listed under each category?
- What is the total number of reviews per category?
- Which products have the highest average ratings?
- What is the average actual price vs the discounted price by category?
- Which products have the highest number of reviews?
- How many products have a discount of 50% or more?
- What is the distribution of product ratings (e.g., how many products are rated 3.0,
  4.0, etc.)?
- What is the total potential revenue (actual_price × rating_count) by category?
- What is the number of unique products per price range bucket (e.g., <₹200,
₹200–₹500, >₹500)?
- How does the rating relate to the level of discount?
- How many products have fewer than 1,000 reviews?
- Which categories have products with the highest discounts?
- Identify the top 5 products in terms of rating and number of reviews combined.

### Data Analysis
This is where we include some formulas during your analysis
```MS Excel
=IF([@[Actual Price 2]]<200,"<₹200",IF([@[Actual Price 2]]<=500,"₹200-₹500",">₹500"))
=IFERROR(E2*J2,"N/A")
=I2*J2

### Data Visualization



