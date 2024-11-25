# JACKSLURR-MERCHANTS`-DASHBOARD
This power Bi project shows analysis of sales, employees, customers and shipping and how all of these have affected employee-customer relationship. 

![pexels-pixabay-48820](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/61b9678d-017d-4e46-b560-b170e506661e)


## OVERVIEW
This data analysis project aims at exploring the relationship between employees and their customers while examining properly the sales trend, sales performance of products, the company`s return (Revenue and profit) as well as their services rendered through deliveries and shipping of these products. The JACKSLURR traders analysis is a power BI based project through which we will gain insights that shall cover extensively four areas:
 
1) Sales
2) Employee performance
3) Customer information
4) Shipping
   
To properly do this, we will perform data cleaning, and appropriate use of power query editor. We shall explore data analysis functions (DAX) to get our KPIs and other definitive analysis to help us gain more insights.

## INTRODUCTION
By analyzing the datasets related to the Jackslurr traders which covers information of their sales, products, customers, workers and shipping, we shall answer the following basic questions:

## SALES

- What are the top 5 countries by revenue?
- Show the trend of profit made over the years
- What category of products generate the highest revenue, and what product sell the most?
- Show the amount generated from sales in each month
- Which countries contribute more to the revenue of the company

## EMPLOYEES

- Find out the best employees as well as the worst
- Show how each employee delivered products ordered; find out if they delivered effectively or didn’t deliver at all.

## CUSTOMERS

- Which customers were given the highest discount over the years and show the corresponding quantity of products they bought?
- How many customers didn’t get their ordered products delivered to them and how many times.
- Top 3 customers who have made the highest orders
- Top 3 customers who have generated the highest revenue for the company
- Who stands as the best customer for 2015?

## SHIPPING
- What shipping company render the best delivery service?
- Show the quantity of goods shipped by each shipping company
- What is the best delivery day?
- What country has spent more in shipping her product?

However, in the course of this analysis, I was able to ask deeper questions outside the questions above, the aim was to get detailed insights without losing sight of our primary questions.

My goal is that by the completion of this project, we must have had a detailed understanding of the jackslurr traders employee`s behavior in relation to their customers, the overall shipping service as well and how this has affected the sales of the company. The result of our analysis could help the company know the customers to focus on, what category of products to enhance, what shipping company to prioritize, what employee to promote and those to encourage and then how best to optimize the general service it renders.
The project could also provide valuable insights for entrepreneurs, business organizations, and managers to devise strategies for sustainable business management and enhance worker-customer relationship.

## I demonstrated the following skills in this project:
- Data cleaning
- Dax
- Modelling
- Buttons
- Page navigation
- Data visualization,
- Measures,
- Filters
- Tooltips,
- Critical thinking,
- Problem solving.
  
I obtained the data by downloading the csv file from my drive and then imported into my power BI desktop. The data is a sample data of a public available datasets on company sales. Thus, ***This dataset and report do not represent any real organization; they are simply a demostration of my proficiency in the use of power BI.*** The dataset has seven (7) tables providing data of :
products of the company; categories of these products, orders and all its details; employee details and details of shipping and deliveries all of which ranged from the year 2013 to 2015.

## DATA TRANSFORMATION/CLEANING
The dataset I worked with did not really require much cleaning, so I first checked for null values and empty columns, I found an empty column in the “report to” column of the “Employee” table so I replaced it with the average of the values of the column 

**Some other Cleanings include:**
- Making first role Headers
- Changing Data Types
- Renamed columns
- Replaced values

I also proceeded to inserting new columns like sales, profit, actual waiting days and delivery status. for effective analysis, I Merged the orders table with the customer table and named it “Merge 2”.

## DATA MODELLING
I ensured that my tables were modelled rightly for proper analysis.

**Below are the KPIs for this analysis.**
1) Total Revenue
2)	Average Revenue
3)	Count of sales
4)	Number of customers
5)	Total discount
6)	Number of employees
7)	Average shipping days
8)	Total orders placed
9)	Quantity ordered
10) Sum of freight
11) Number of products


After this, I proceeded to analyzing my data.
Analysis and problem solving.
I analyzed the data step by step according to the questions and aim of my analysis. However, outside the basic questions which my analysis covered, we shall discover that some other questions where answered.


**Our first analysis**, is on the **The sales dashboard**

<img width="737" alt="Jackslurr sales" src="https://github.com/user-attachments/assets/b4c22cb0-f5fb-4d69-8f19-2e4415367947">

 Notice that the profit rose in 2014 and fell greatly in 2015 as seen here:

![Profit by year](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/78af9918-3f4c-4e77-8682-1a8b3a20d41d)

This is most likely to be as a result of the decline in sales in 2015. The year 2015 recorded a total sales of 691 as against 1059 sales that was made the previous year. 
The result of this drop in sales is surely a reaction of customers dissatisfaction. Moving further however, we shall throw more light on this.

Another very evident fact is that the highest sales by month was recorded in April but fell drastically the following months especially in June before it started picking up again.

![Sales by month](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/5d35cdd2-8959-4848-b9bb-6e050eed6211)


**The dashboard is an interactive one and so further findings can be explored.** 

[click here to interact with the dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmRkNzUxZWItYzBhZi00Y2RhLTlmODgtNjIwODIzNjJjN2ZiIiwidCI6ImY4NzNhMzA5LTg2ZjgtNDg4OS05OTcxLTEzMDQwNDM0NjZmNCJ9)

**In the employees dashboard**,

<img width="650" alt="Jackslurr Employees" src="https://github.com/user-attachments/assets/a3bb2542-3f01-4e98-98c2-fd64b8be07a7">

we see that some employees distinguished themselves. Very evident is that **Margaret Peacock** stands as the best employee.

![Number of customers attended to](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/9eb2d00c-8346-4153-9067-c77eb5fab82d)

![Employee with highest sales](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/c4151057-3fa4-406e-9e86-d87f9f91b45b)

![Employee with highest revenue](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/f633c7f6-f6ed-47e6-bb67-4381217ccd5f)

As we can see above, she attended to the most customers (75), sold the highest number of products and even generated the highest revenue for the company. However, it is important also to note that there were times she delivered products late (10 times) and there were times she never delivered at all (5 times).

From the analysis, the worst employers has to be between Michael Suyama and Steven Buchanan. 

![Employee with lowest revenue](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/76280b8e-2f2a-48e3-97fb-9965a937f9ac)

This is because they generate the least revenue for the company. Although Michael Suyama attended to more customers (43) than Anne Dodsworth who attended to only 29 customers just as Steven Buchanan.  But then, Anne Dodsworth generated more revenue for the company. However, credit should be given to Steven Buchanan who despite generating the least revenue has had only one (1) late delivery.

**In the third dashboard “Customers”**,

<img width="658" alt="Jackslurr Customer" src="https://github.com/user-attachments/assets/493d1e01-2c3a-4de0-b31e-3215e943c1d8">

We notice that the three (3) customers that generate the highest revenue for the company are same customers making the highest orders. This could be the reason why all three customers have the highest discounts when compared with other customers.
the image below explains better

![Customers with highest orders](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/530da9e4-b805-448d-951e-171e110be091)

![Customer and discount value](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/0c3cd04c-5fbc-4756-ba25-e7b5f2acc21c)

Notably, one amongst these “best” customers Roland Mendel didn`t get some of his products delivered to him on two occasions as shown below:

![Customers with underlivered products](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/f3a8cec2-3634-4739-b9f1-58156ace1a54)


**In the fourth dashboard** 

<img width="651" alt="Jackslurr 1" src="https://github.com/user-attachments/assets/9293600d-ba5d-4e80-a9dd-e842097ffcaf">

This analyzes all about shipping and orders, we see that it takes on average, 8 days for ordered products to be shipped and Thursday happens to be the worst day for shipping products as indicated in our visual:


![Quantity delivered by working days](https://github.com/NonsoSk/JACKSLURR-MERCHANTS-DASHBOARD/assets/147613828/f38e04de-1f6b-42ba-9df4-f7a964620344)

Very importantly is the fact that the only time the company failed to ship products ordered was in 2015, specifically in the months of April and May.


## RECOMMENDATIONS AND CONCLUSIONS 

- From our analysis, it is clear that there was a great fall in sales in the year 2015, this as we know resulted from the poor delivery and shipping service  which was recorded that year. It is a thing of concern that despite the fact that the company holds a good record in delivering products even  early, the little slack in failing to deliver products only 21 times had such a great impact in its sales. To this, **I will recommend that the company optimizes her shipping strategies to make sure that every product is delivered.**
- The month of July recorded the highest sales which was immediately followed by reoccurring low sales. This also is an indication of customer dissatisfaction. The worry however is in the fact that the sales never rose again even till December. This is an indication that the company never took time to make analysis of their sales all through. **I thus recommend a monthly review and corresponding analysis of the company`s data to help the company understand customer behavior and sales pattern.**
  
- I observed that one Employee (Margaret Peacock) distinguished herself very positively. **I recommend that she be awarded for her relentless services. An increment in her salary would go along way to encourage her and motivate other employees.**
  
- Moving further **I would also recommend that employees be shown gratitude at the end of the year. However, it should be with respect to how well they have served the company. This would facilitate healthy competition among the workers so the gap between the best and the worst worker wouldn`t be much as seen in the case of Margaret Peacock and Steven Buchanan, where Margaret attended to customers 75 times and Steven just 29 times.**

- On the other hand, the customers who generated the least revenue to the company shouldn`t totally be condemned. They should be encouraged though to work harder. **I recommend thus that the company sets up a board to process employees’ feedback to help attend to the needs of employees so as to aid them serve the company better.**
**I also recommend that employees who fail to deliver orders of product to customers be held accountable for it. That is if all needed for the delivery was provided by the company beforehand, else the company should be culpable. This is however a matter to be treated as an inner affair.**

- I observed that Roland Mendel who happens to be one of the best customers of the company ordered the highest number of products, but yet did not generate the highest revenue for the company. This could be that the products he ordered were not as expensive as others who ordered lesser products but generated more revenue. It could also be that he did not generate the highest revenue for the company because some of his products were not delivered as could be seen in our dashboard. This means that when products are not delivered, they affect the customers and also affect the revenue of the company.  **I recommend then that the company makes it up to all the customers whose products were not delivered and that such would not happen again.**

- I observed that the only time products were not delivered was in 2015 and this happened only in April and May. April recorded the highest sales but sales began to decline from the following month.  “United package” despite being the company with the highest number of shipping, failed to ship ordered products 11 times, which is the highest any shipping company ever had. **I recommend thus that shipping companies intensifies its services especially during the rainy seasons.**
  
- Lastly, Outside the fact that the dataset worked on was from January 2013 to may 2015, we still see that decline in sales resulted  greatly from the bad service which was registered in 2015. **I recommend then that Employee-customer relationship be improved, so that employees while maintaining formality in their services, can also become friends (informally) with the customers.** This would help them reach out more friendly to customers whose products were not delivered and sort things out to avoid chasing customers.

### Thanks for Reading......




