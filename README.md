# Sales analysis in retail

## Contextualização

The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. 

## Data analysis plan

#### Goals
In this project, I do the data analysis in retail of three branchs during the three months in order to answer the following questions:

1. Which is the average of sales during all time?
2. Which product line have the biggest percentage of purchase?
3. Which is the profile of the customers? 
4. Which day of the month has the highest selling average?
5. Which branch has the highest selling average? Can it possible to filter the results?


#### Data source

The *dataset* used in this project is available to download in https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales.

The table has 17 colunms:
- Invoice id: Computer generated sales slip invoice identification number
- Branch: Branch of supercenter (3 branches are available identified by A, B and C).
- City: Location of supercenters
- Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
- Gender: Gender type of customer
- Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
- Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
- Unit price: Price of each product in $
- Quantity: Number of products purchased by customer
- Tax: 5% tax fee for customer buying
- Total: Total price including tax
- Date: Date of purchase (Record available from January 2019 to March 2019)
- Time: Purchase time (10am to 9pm)
- Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
- COGS: Cost of goods sold
- Gross margin percentage: Gross margin percentage
- Gross income: Gross income
- Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

#### Tools used:

![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)   ![Dash](https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

All analysis was made in MySQL, but the dashboard was built using Python, Dash, HTML and CSS. To have a better experience with the dashboard, get access in the desktop screen.

Click on here to get access the dashboard.

#### Techniques applied:

Aggregation, view materialized, subqueries, attributes transforming, parsin, and so forth.

## Conclusions

The answers of the listed questions and the others that you, my dear reader, must have can be solved using the filters and the iteractive datatable.

