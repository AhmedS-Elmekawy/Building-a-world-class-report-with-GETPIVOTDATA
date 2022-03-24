# Building-a-world-class-report-with-GETPIVOTDATA

> In this project we'll be building a model that allows you to elaborate large quantities of data by getting the best of Pivot Table functionalities (GETPIVOTDATA, Slicers), that can improve the reporting of any firm.

> We'll be using a sample of a Fast moving consumer good industry (FMCG), that involves the production, Sales of non-durable goods such as (soft drinks, processed food & other consumable goods) It's known for its high volumes, Lower Margins & Large Product Portfolios.

#### Usually, Several firms are competing for market share & this makes financial transparency & insight even more critical.

## We'll be analyzing the data set for: 
1. What are the most profitable products
2. Which packages of these products are preferred by clients
3. What is the optimal size clients prefer to buy 
4. Furthermore, they operate with a number of key clients and need to find out what's the best course of action to take

## Our main goal is to build a model that allows the company management to see: 
1. The volumes that were sold 
2. The Revenue
3. Margins that were obtained
4. Provide a breakdown per month for
   1. Client & Client Type
   2. Brand 
   3. Size & Pack 
   
#### These are the important indicators that need to be analyzed to understand whether the company can improve its product offerings.

## Our dataset which was extracted from ERP System  we'll be working with has two types of information
1. Descriptive information about our products:
    1. Material Number (e.g; 12125200)
    2. Material Description (Brand, Size, Pack, Client e.g; Dundy Diet 600ML 6X)
    3. Period (Year & Month e.g; 201601)
    4. Client Type (e.g; Supermarkets, Grocery, Big-box or Discounters)
2. Financial information about the products' sales that we're going to analyze:
    1. Volume (amount of sales)
    2. Gross sales
    3. Discounts (Clients receive different discounts based on the amount of business they generate)
    4. Net Sales (Gross sales - discounts)
    5. Cost of goods (How much's spent to produce the product)
    6. Distribution (transport expenses that have been sustained to deliver the product to the client)
    7. Warehousing (The cost for keeping the items in the company's warehousing facilities)
 
 > The dataset contains 88,453 records & expands across multiple columns 

## Structure of the report for the data we've extracted from SAP (Creating an Output Structure):

1. Volume (One of the most important drives for businesses is volume sold)
2. Gross Sales income (Revenue for the company before it starts providing discounts for the client)
3. Discounts
4. Net Sales (Gross Sales Income - Discounts), it's the primary sales figure viewed by analysts when conducting a financial analysis.
5. Cost of goods sold
6. Gross Profit (Net sales - Cost of goods), preliminary profit measure that shows how the business makes after taking into consideration the cost of the products
7. Distribution
8. Warehousing Expenses
9. Full delivered Margin, Profatibilty measure that shows how much profit the firm makes when taking into account (the production, warehousing & Transportation)
