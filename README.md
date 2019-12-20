# Title

Consumption habits, for a healthier way of life

# Abstract

The study of consumption habits is a very hot topic as it can be very useful for marketing issues, or advertisement. However, our goal here is to use data in order to help consumers directly. We give some advice regarding consumption to reorient clients’ habits toward a healthier way of life. In this project, we use purchases history of Instacart (an online delivery service) to identify the main tendencies. We expected to highlight preferred days or hours of the day to go shopping, but discovered that the consumption habits are not correlated with the healthiness of the users. However, we found links between the products, and thus were able to advise healthier alternatives to the users, hence allowing to plan a smooth transition to a more responsible consumption.

# Research questions

Can we classify consumers depending on the categories of products they buy (aisles and departments) and their repartition (fresh products, cooked meals, cans, …)?
Can we define one of this group as the  “healthier consumption”, toward which people should tend to?

What are the consumption habits of consumers groups, especially the healthier one (day of the week, hour of the day, time since the previous order, number of orders, quantity ordered, reordering rate) ?

Can we find equivalent products between the different consumers groups (by aisles), and thus offer healthier alternative products ? Which one should be advised, based on reorders ?


# Dataset

Instacart dataset (provided) : https://www.instacart.com/datasets/grocery-shopping-2017
This dataset consists in 4 different tables with data regarding the orders, the products and some categorization of the products. It also contains one dataset retracing the history of orders per product and per client.

We explored the Amazon product reviews : https://cseweb.ucsd.edu/~jmcauley/datasets.html?fbclid=IwAR39s5O83nqUYkRBD4jol3OFu0FmcH-4dCzUtSjutOsmSd9LMZOHSGGtNxw#amazon_reviews
It’s a JSON document, providing references of products associated to ratings and reviews. We wanted to use this dataset to establish an average price of the products by category (aisles), and thus get an idea of the budget of each costumer.

# Material

The data story can be found following the link : https://eloilit.github.io/?fbclid=IwAR0bPklrxY5POWP5xcHZKq4ghEekMgjfQ8BEOUid5ZERMAsojjDRoPIxKqs

Please read notebook "main_project", being the last up to date progress report.

# Participation

Auriane Cozic : pre-analysis, clustering
Ariane Delrocq : Amazon dataset, graph (links between products)
Pierre Liorit : reordering studies
Eloi Litner : data story
All members supervised and proofred the all code
