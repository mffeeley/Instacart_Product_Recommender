# Instacart Product Recommender
This project was done as part of my experience at [Metis](https://www.thisismetis.com/data-science-bootcamps).

## Project Intro/Objective
The objective for this project is to develop a model that recommends a product to a user in the purchasing funnel on [Instacart.com](https://www.instacart.com).  This is done by using user [order history](https://www.kaggle.com/c/instacart-market-basket-analysis/data) to predict whether or not a product will be in the user's next cart.

### Methods Used
* Classification
* Predictive Modeling
* Machine Learning

### Technologies 
* Python
* numpy
* pandas
* Matplotlib
* scikit-learn
* imblearn

## Project Description
The order history has details for every order including time, day, each product and the order it in which it was added to the user's cart, which order it is for the user chronologically, and how many day have passed since the user's last order.  The data is aggregated to engineer features from that extract more insight into user purchasing trends at a user level, product level, and user-product level.

The project contains two notebooks:

* **Preprocessing:** Unloads the data, engineers the features, and saves the data to a pickle file.
* **Modeling** Loads the preprocessed data and creates the model.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Download the data [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data)

## Authors
* [**Michael Feeley**](https://www.linkedin.com/in/mffeeley/)
