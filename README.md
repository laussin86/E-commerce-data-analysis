# E-commerce-data-analysis
 **SUMMARY**
 
 My analysis has been divided in 3 part: Sales Analysis, Customers Analysis and Predictive Analysis. The Goal of those analysis is to find people who buy the most and the less, what they are buying. Also what is the most selling product and finally predict future sales using SARIMAX statistic model. Note that all the data required for each analysis has been done by using SQL queries to extract the required data.

 1- **SALE ANALYSIS**

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


Our further analysis conduct us to find what is the 20 best selling product and product categories

![newplot](https://github.com/user-attachments/assets/2f5119c9-34a8-449f-80ce-043ebd691316)
![newplot (1)](https://github.com/user-attachments/assets/920eb25c-07d3-4b9f-ab58-59e32f1a09a6)

we can see tha beverages are the most selling items. We can also see below that classic Pepsi and Coca-Cola are the top-selling beverages, along with Sprite and Diet Cola. Diet Pepsi has sales that are nearly half of those of classic Pepsi. Regarding healthy foods, they all have similar sales volumes. We see a good number of protein bars and oatmeal

![newplot (3)](https://github.com/user-attachments/assets/a3c494c5-5c5a-4c1c-80e9-8e32e44cd07a)
![newplot (2)](https://github.com/user-attachments/assets/81d45d1f-bfc9-407b-b0cf-67e11ebbccb8)

In regards to the top expensives items, we have k cups items

![newplot (4)](https://github.com/user-attachments/assets/cfe6f137-20ea-4d4b-b24e-2a20c61982e3)

2- **CUSTOMERS ANALYSIS**

in this section, I stated by categorizing customers based on the number of purchases by calculating how many purchases each customer has above and below the average transaction cost.

![newplot (5)](https://github.com/user-attachments/assets/f6755428-8a47-4134-bb45-282c83249dde)

As we can see in the graph, 58.5% of customer have transaction cost below average.

The next step was indetified the top 10 customers with the most purchases above the average and the bottom 10 customers with the fewest purchases below the average as see below:

![newplot (7)](https://github.com/user-attachments/assets/c38c02e8-1c68-4af7-bf91-d188b671ce1d)
![newplot (6)](https://github.com/user-attachments/assets/dc6889bb-807e-48a1-88f2-bf7185d024ad)

I wanted also to know what is the Top Items Bought by Customer Above Average and the Top Category Bought by Above Average Customer as you can see below:

![newplot (9)](https://github.com/user-attachments/assets/14e85f13-823e-4b2f-8cfb-4958750e560c)
![newplot (8)](https://github.com/user-attachments/assets/cadd26e2-828c-407e-bcf4-909a7634ba73)

3- **PREDICTIVE ANALYSIS**

Our last part was to predict the total sales within the next months using SARIMAX stat models who gave us a Mean Absolute Percentage Error (MAPE) of ~6.8%

![image](https://github.com/user-attachments/assets/e1fffeca-d8ff-4e23-b139-375e3514f5dc)

 **RECOMENDATIONS**

 
