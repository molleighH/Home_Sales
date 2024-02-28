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

<img src="https://github.com/molleighH/Home_Sales/blob/main/Resources/15.png" width="650" height="300" border="10"/>


## Conclusion 
Based on the runtime results, cached data and the parquet data are both faster than the original data. This is attributed to optimizations offered by caching and parquet data format. 

Caching the data always storing the data in memory. This is a great way to speed up queries, because it is retrieving directly from memory, which elminates the need for reading the data from disk. 

Parquet in a columnar storage file format designed to improve data storage efficieny, to improve query performance & speed processing, to improve compatibility with various big data frameworks/ecosystems. I believe the the parquet formatted data is meant to demonstrate the best runtime among the three options this module has explored; despite, what times my laptop recorded. This may be attributed to optimized storage format, efficient compression, and the ability to leverage columnar optimisations during query exectuion of the data. In using parquet and it's abilities, a faster query performance, a reduced storage requirement, and  an imporved overall data processing efficiency is most likely to occur.  