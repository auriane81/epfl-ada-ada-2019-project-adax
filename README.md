# Title

Consumption habits, for a healthier way of life

# Abstract

The study of consumption habits is a very hot topic as it can be very useful for marketing issues, or advertisement. However, our goal here is to use data in order to help consumers directly. We want to give some advice regarding consumption to reorient clients’ habits toward a healthier way of life. In this project, we will use purchases history of Instacart (an online delivery service) to identify the main tendencies. We expect, for example, to highlight preferred days or hours of the day to go shopping. We also aim to find correlations between the products bought, and thus healthier alternatives, hence allowing to plan a smooth transition to a more responsible consumption.

# Research questions

Can we classify consumers depending on the categories of products they buy (aisles and departments) and their repartition (fresh products, cooked meals, cans, …)?
Can we define one of this group as the  “healthier consumption”, toward which people should tend to?

What are the consumption habits of consumers groups, especially the healthier one (day of the week, hour of the day, time since the previous order, number of orders, quantity ordered, reordering rate) ?

Can we find equivalent products between the different consumers groups (by aisles), and thus offer healthier alternative products ? Which one should be advised, based on reorders ?

How does each consumer budget depend on the categories of products he buys ? May a healthier comsumption shift this budget ?


# Dataset

Instacart dataset (provided) : https://www.instacart.com/datasets/grocery-shopping-2017
This dataset consists in 4 different tables with data regarding the orders, the products and some categorization of the products. It also contains one dataset retracing the history of orders per product and per client.

We would like to enrich it with Amazon product reviews : https://cseweb.ucsd.edu/~jmcauley/datasets.html?fbclid=IwAR39s5O83nqUYkRBD4jol3OFu0FmcH-4dCzUtSjutOsmSd9LMZOHSGGtNxw#amazon_reviews
It’s a JSON document, providing references of products associated to ratings and reviews. We will use this dataset to establish an average price of the products by category (aisles). This will allow us to get an idea of the cost of each order, and thus the budget of each costumer.

#Note for the TAs

Please read notebook "main_project", being the last up to date progress report.

# A list of internal milestones up until project milestone 3

02/12 : Clustering of the consumers, based on the products they buy and their category. Manually label each cluster on a 'healthiness scale'

07/12 : Visualize consumption habits depending on the consumer cluster.
Associate a budget for each consumer cluster.

10/12 : Search for products equivalents between consumers groups, based on the aisles.
Define the probability of each product to be reordered.

14/12 : Advise healthy alternative products to each consumer groups.

20/12 : Design the data story and redact the report
