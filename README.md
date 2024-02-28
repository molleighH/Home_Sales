# Home_Sales
## Introduction 
Use my knowledge of SparkSQL to determine key metrics about home sales data; then, use Spark to create temporary views, partition the data, cache &amp; uncache a temporary table, &amp; verify that the table has been uncached.

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/house%20for%20rent%20.png" width="800" height="600" border="10"/>

## Findings
##### 3.What is the average price for a four bedroom house sold per year, rounded to two decimal places?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/3.png" width="350" height="350" border="10"/>

##### 4.What is the average price of a home for each year the home was built, that have 3 bedrooms and 3 bathrooms, rounded to two decimal places?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/4.png" width="350" height="420" border="10"/>

#####  5.What is the average price of a home for each year the home was built, that have 3 bedrooms, 3 bathrooms, with two floors, & are greater than or equal to 2,000 square feet, rounded to two decimal places?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/5.png" width="350" height="450" border="10"/>

##### 6. What is the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000? Order by descending view rating. Runtime?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/6.png" width="350" height="500" border="10"/>

##### 9.Using the cached data, run the last query above, that calculates the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000 Runtime?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/9.png" width="350" height="500" border="10"/>

##### 13.Using the parquet DataFrame, run the last query above, that calculates the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000. Runtime?

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/13.png" width="700" height="900" border="10"/>

##### 15.Check if the home_sales is no longer cached

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/15.png" width="450" height="350" border="10"/>