# Product Recommendation System for E-commerce Project

## Project Background
This project improves product recommendations and tracks market trends for an online store. A **SQL**-based data warehouse was set up to store customer and sales data. The project analyzed **10,000** customer records, predicted sales trends, and created personalized recommendations using **Python** to enhance user experience. These insights help businesses find profitable areas and improve marketing, leading to growth and happier customers.

## Dataset Structure 
The dataset for this project was organized into a SQL-based data warehouse with multiple tables for customer data, sales records, product information, and regional market data. The primary data structure used for this analysis and modeling is the combination of two major sources:

  * [Superstore Data](https://github.com/Mamta013/Product-Recommendation-System/blob/main/data/Superstore-Data.csv): Superstore purchase history and revenue data.
  * [Superstore Reviews Data](https://github.com/Mamta013/Product-Recommendation-System/blob/main/data/Superstore-Dataset-Reviews.csv): Rating, review and summary of the product given by the customer. 
    
Note: The dataset comprised 10,000+ records, divided into 36 columns, the feature-target description you can see [here](https://github.com/Mamta013/Product-Recommendation-System/blob/main/data/Features_Target_Description.txt).


## Executive Summary
This project built a **SQL**-based Superstore Data Warehouse and developed product recommendation models to enhance customer experience and sales strategies. By analyzing data from **10,000** customers, the system identified profitable market segments, predicted sales trends, and provided personalized product recommendations.  

Key insights included the **Consumer** segment being the most profitable, **California** as the top-performing market, and strategies to improve underperforming regions like **North Dakota**.


## Codes
* The targed **SQL queries** regarding various business questions can be found [here](https://github.com/Mamta013/Product-Recommendation-System/blob/main/notebooks/Products-Analysis.sql).
* The **Python Pipeline** used for EDA, Model Building for Recommendation Systems and Deployment of model can be found [here](https://github.com/Mamta013/Product-Recommendation-System/blob/main/notebooks/Product-Recommendation-Project.ipynb).



Here’s a refined version with improved clarity and conciseness while keeping the original intent intact:  

---

## **Insights**  

#### **Category 1: Profitable Market Segment**  
   * The **Consumer** segment generates the highest revenue and profit, making it the most valuable customer group.  

#### **Category 2: Top Performing Region**  
   * **California** is the largest and most profitable market, significantly contributing to total sales.  

#### **Category 3: Underperforming Markets**  
   * **North Dakota** is an underperforming market that requires strategic attention to improve profitability and market share.  

#### **Category 4: Growth Forecast**  
   * Sales are projected to rise in **Q4 2018**, presenting opportunities for targeted marketing efforts.  


## **Recommendations**  

#### **Category 1: Capitalize on Growth Opportunities**  
   * Increase marketing efforts in **Q4 2018** to maximize sales during the expected growth period.  

#### **Category 2: Focus on the "Consumer" Category**  
   * Implement targeted marketing campaigns, personalized promotions, and enhanced customer experiences to boost profitability in the **Consumer** segment.  

#### **Category 3: Optimize Market Strategies**  
   * Continue investing in **California** through strategic marketing, customer retention programs, and efforts to expand market share.  

#### **Category 4: Improve Underperforming Markets**  
   * Conduct detailed market research in **North Dakota** to tailor marketing strategies and boost sales.  


## **Assumptions and Caveats**  

#### **Assumptions:**  
* The data accurately represents customer preferences and purchasing patterns.  
* Sales forecasts are based on historical trends, assuming no major market disruptions.  

#### **Caveats:**  
* External factors like economic shifts or unforeseen events may affect sales trends.  
* Recommendation models rely on existing data and may be less effective if customer preferences change or if data is insufficient for new products.  

