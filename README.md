# Project: E-Commerce-Customer-Segmentation-Project

## Description

Analysis of an `E-Commerce customer database` that lists purchases made by over 4000 customers over a period of one year, I developed a model that allows to anticipate the purchases that will be made by a `new customer`, during the following year, from its first purchase.

## Business Use-case Overview
`Customer segmentation` is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to `marketing`, such as `age`, `gender`, `interests` and `spending habits`. and also be seen as the practice of dividing a `company’s customers` into groups that reflect similarity among customers in each group. The goal of segmenting customers is to decide how to relate to customers in each segment in order to maximize the value of each customer to the business

Companies employing customer segmentation operate under the fact that every customer is different and that their `marketing efforts` would be better served if they `target specific`, `smaller groups` with messages that those costomers would find relevant and lead them to buy something. Companies also hope to gain a `deeper understanding` of their `customers' preferences` and needs with the idea of discovering what each segment finds most valuable to more accurately `tailor marketing materials` toward that segment.

Customer segmentation relies on identifying key differentiators that divide customers into groups that can be targeted. Information such as a customers' demographics (age, race, religion, gender, family size, ethnicity, income, education level), geography (where they live and work), psychographic (social class, lifestyle and personality characteristics) and behavioral (spending, consumption, usage and desired benefits) tendencies are taken into account when determining customer segmentation practices.


## Install
This project requires Python 3.7 and the following Python libraries installed:

* Numpy
* Pandas
* matplotlib
* scikit-learn

You will also need to have the software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the `Anaconda distribution` of Python, which already has the above packages and more included. Make sure that you select the Python 3.7 installer and not the Python 2.x installer.


## Data
The customer segments data is included as a selection of app. 4000 data points collected on data found from an E-Commerce database, which was gotton from UCI Machine Learning Repository. You use this data in your local machine, you have to clone and unzip the `data.csv` file from this Repo.  

### Features
This dataframe contains 8 variables that correspond to:

1. **InvoiceNo**:  Invoice number. `Nominal`, a `6-digit integral` number uniquely assigned to each transaction. If this code starts with letter `'c'`, it indicates a cancellation.
2. **StockCode**: Product (item) code. `Nominal`, a `5-digit integral` number uniquely assigned to each distinct product.
3. **Description**: Product (item) name. `Nominal`.
4. **Quantity**:  The quantities of each product (item) per transaction. Numeric.
5. **InvoiceDate**: `Invoice Date` and `time`. `Numeric`, the day and time when each transaction was generated.
6. **UnitPrice**: `Unit price`. `Numeric`, `Product price` per unit in sterling.
7. **CustomerID**: `Customer number`. `Nominal`, a 5-digit integral number uniquely assigned to each customer.
8. **Country**: `Country name`. `Nominal`, the name of the country where each customer resides.

#### DataFrame 
![data init head](https://user-images.githubusercontent.com/25388109/86505675-d220f580-bdbf-11ea-8260-c165bf645c63.png)


## Code

Template codde is provided in the `E-Commerce Customer Segmentation.ipynb` notebook file. You will also be required to use the `data.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. 

## Run

In a terminal or command window, navigate to the top-level project directory `E-Commerce Customer Segmentation.ipynb`/ (that contains this README) and run one of the following commands:

When you're ready, fire up the notebook.

```ipython notebook E-Commerce Customer Segmentation.ipynb```

or

```jupyter notebook E-Commerce Customer Segmentation.ipynb```

This will open the Jupyter Notebook software and project file in your browser.


# Data Exploration

![newplot](https://user-images.githubusercontent.com/25388109/86505481-152d9980-bdbd-11ea-9d45-5a8292671f31.png)

From the Map, You'll see that the dataset is largely dominated by orders made from this first five Countries

* `United Knigdom` with `19857` customers
* `Germany` with `603` customers
* `France` with `458` customers
* `EIRE` with `319` customers
* `Belgium` with `119` customers



#### keywords Word Occurence 

![word occurence 1](https://user-images.githubusercontent.com/25388109/86505722-4fe50100-bdc0-11ea-9a91-b4f971b594f3.png)
![word occurence 11](https://user-images.githubusercontent.com/25388109/86505724-52475b00-bdc0-11ea-8373-07fef750c573.png)
![keywords occurence 3](https://user-images.githubusercontent.com/25388109/86505803-11037b00-bdc1-11ea-84cc-7bae63eb13e1.png)



#### Product Content Word cloud

![word cloud](https://user-images.githubusercontent.com/25388109/86505858-8ec78680-bdc1-11ea-8fcc-5354a5767830.png)



#### PCA Customer category analysis

![PCA analysis 11](https://user-images.githubusercontent.com/25388109/86505918-18775400-bdc2-11ea-9508-40b33ddc3da9.png)


#### Customers morphology


![customer morphology 1](https://user-images.githubusercontent.com/25388109/86505974-a81d0280-bdc2-11ea-9eb7-cc42b2fe055a.png)
![customer morphology 11](https://user-images.githubusercontent.com/25388109/86505976-ac492000-bdc2-11ea-935b-c59341fecd37.png)



#### Classifiers and respective learning curves


![adaboost_learning_curve](https://user-images.githubusercontent.com/25388109/86506016-1feb2d00-bdc3-11ea-81bc-5ca083bf8916.png)
![decision_tree_learning curve](https://user-images.githubusercontent.com/25388109/86506017-211c5a00-bdc3-11ea-8813-0f0d7f3b2222.png)
![gradient_boosting_clf_learning_curve](https://user-images.githubusercontent.com/25388109/86506018-21b4f080-bdc3-11ea-916e-ee4270d2579b.png)
![knn_learning curve](https://user-images.githubusercontent.com/25388109/86506019-224d8700-bdc3-11ea-992c-e43120a2d454.png)
![lr_learning curve](https://user-images.githubusercontent.com/25388109/86506021-24afe100-bdc3-11ea-87ab-110886ca2f91.png)
![random_forest_learning_curve](https://user-images.githubusercontent.com/25388109/86506022-25487780-bdc3-11ea-88a8-5ba35d71c89f.png)


# Installation

# Contributing

