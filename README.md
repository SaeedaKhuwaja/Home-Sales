# Home-Sales - Challenge 22

## Background

In this challenge the knowledge of Spark is used to create temporary views, partitioning the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Process Explained

The data is first read from the csv file in spark datafram and then temporary view table is created to answer the following questions.
1. What is the average price for a four-bedroom house sold for each year?
2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query.

The homesales data is then cached and runtime is calculated. The runtime is then compared with the uncahed data. Through this overall process it is found out that the uncached version took a little more time than the chached version.
