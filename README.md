# E-commerce-data-analysis
 **SUMMARY**
 
 My analysis has been divided in 3 part: Sales Analysis, Customers Analysis and Predictive Analysis. The Goal of those analysis is to find people who buy the most and the less, what they are buying. Also what is the most selling product and finally predict future sales using SARIMAX statistic model. Note that all the data required for each analysis has been done by using SQL queries to extract the required data.

 1- **Sales Analysis**

 The first analysis was to find was the most prefered method of payment:

 ![image](https://github.com/user-attachments/assets/0864a31c-a4c3-4b68-bf4e-c4f735f1696f)

As per the graph, We can see that the prefer payment type is card. Also, We can see most of the product has price between 12 and 28 and most transaction have a value between 5 and 100:

![image](https://github.com/user-attachments/assets/ca8407db-3555-49a2-b57b-00935447df62)
![image](https://github.com/user-attachments/assets/f010ae98-ec84-40bc-9971-bed2c64b498e)

I noticed also that Bangladesh is chosen the most for manufacturing and DENIMATCH LTD is the first supplier.

![image](https://github.com/user-attachments/assets/f9128974-8e72-4059-822b-2dda7efb6a6a)

Below, we can see the sales trend over time and per division over time:

![newplot](https://github.com/user-attachments/assets/1a6b88f4-82d6-4c1e-9064-9a32eb86e664)
![newplot (1)](https://github.com/user-attachments/assets/d2a3c762-2aa0-4d6c-8e9e-6f2084e89ff4)

We can state that the division with the highest sales over the years has been Dhaka, and just below is Chittagong

We pushed our analysis to see the total sales by months and days:

![newplot (3)](https://github.com/user-attachments/assets/5143340e-aec6-479b-bebe-151ce15fd844)
![newplot (2)](https://github.com/user-attachments/assets/d4344ced-75d0-45c4-86a4-3e72a166d6ae)

with this graphs, we can confidently confirm that the sales drop in the 2 month february with the lowest total sales, followed by April and then June, while May is the month with the highest sales volume. Daily sales are costant, we can only see a diminish in sales terms after the 30th day, but it's because some month have 31 days


