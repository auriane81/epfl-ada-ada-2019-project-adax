# Title

Consumption habits, for a healthier way of life

# Abstract

The study of consumption habits is a very hot topic as it can be very useful for marketing issues, or advertisement. However, our goal here is to use data in order to help consumers directly. We want to give some advice regarding consumption to reorient clients’ habits toward a healthier way of life. In this project, we will use purchases history of Instacart (an online delivery service) to identify the main tendencies. We expect, for example, to highlight preferred days or hours of the day to go shopping. We also aim to find correlations and incitations between the products bought, hence allowing to plan a smooth transition to a more responsible consumption.

# Research questions

Can we classify consumers depending on the categories of products they buy and their repartition (fresh products, cooked meals, cans, …)?
Can we define a “healthy consumption” people should tend to?

How do the consumption habits of a particular client depend on the moment he orders (day, hour and time since the previous order) ?

How are purchases influenced by the previous ones ? For instance, which products tend to be reordered ; and what products incitate to buy another one ?


# Dataset

Instacart dataset (provided) : https://www.instacart.com/datasets/grocery-shopping-2017
This dataset consists in 4 different tables with data regarding the orders, the products and some categorization of the products. It also contains one dataset retracing the history of orders per product and per client. 

We would like to enrich it with Amazon product reviews : https://cseweb.ucsd.edu/~jmcauley/datasets.html?fbclid=IwAR39s5O83nqUYkRBD4jol3OFu0FmcH-4dCzUtSjutOsmSd9LMZOHSGGtNxw#amazon_reviews
It’s a JSON document, providing references of products associated to ratings and reviews. We will use this dataset to establish some statistics on the prices distribution for a given product and thus quantify the quality of the product. This information will help us to determine the consumers’ wealth, and separate them into different categories. 


# A list of internal milestones up until project milestone 2

01/11 : Download the required data and set up the environment

08/11 : Explore the dataset, find the issues and clean it

11/11 : Classification of the products by quality, thanks to the Amazon dataset

15/11 : Classification of the consumers depending on the kind of products they buy

18/11 : Visualize consumption habits depending on the time features (hour, day, last command), and look for correlations

22/11 : Design and add a field for each product, measuring its probability to be reordered.

Explore the link between the products and their ordering, trying to build a “path” toward healthier ones
		
25/11 : Debug and comment the code


# Questions for TAa

Is it too big an assumption to infer the quality and wealthiness of a product based on its price (compared to the prices of other similar products) and clients’ review ?
