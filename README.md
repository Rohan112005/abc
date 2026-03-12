# Credit Card Default Prediction

## Project Overview

This project is about using machine learning to figure out if a credit card customer will miss their payment. If a customer misses a payment it is called a default.

Banks lose money when customers do not pay their credit card bills on time. By looking at what customers have done in the past a machine learning model can help identify customers who might miss payments in the future.

The goal of this project is to build a machine learning model that can look at past customer data and predict if a customer will default on their credit card payment.

---

## Dataset

The dataset used in this project has information about credit card customers.

Some important things in the dataset include:

* How credit a customer has

* If the customer is a man or a woman

* What level of education the customer has

* If the customer is married

* How old the customer is

* How the customer paid their bills in the past

* How much the customer had to pay each month

* How much the customer actually paid each month

We want to know if the customer will default on their payment month.

* If the customer pays their bill it is marked as **0**

* If the customer does not pay their bill it is marked as **1**

---

## How Credit Cards Work

A credit card lets a customer borrow money from the bank to buy things. The bank pays for it first. Then the customer has to pay the bank back.

At the end of each month the bank sends a bill to the customer. If the customer pays the bill on time they do not have to pay money. If the customer does not pay the bill it is called a **default**.

Banks want to know which customers might default so they can be careful and not lose much money.

---

## Project Workflow

### 1. Loading Data

We use Python and a library called Pandas to load the dataset. The data is stored in a table so it is easy to look at.

### 2. Cleaning Data

We do some things to make the data easier to work with such as:

* Renaming columns

* Removing columns we do not need like the customers ID

* Checking for missing information

This helps us work with the data easily.

### 3. Looking at the Data

We look at the data to understand it better. We use graphs and statistics to explore the data.

Some things we look at include:

* A graph that shows how many customers defaulted

* A graph that shows how different things are related to each

This helps us see how different things are connected.

### 4. Choosing What to Look At

We divide the data into two parts:

* **Things that might affect if a customer defaults (X)** like how old the customer's how much credit they have and how they paid their bills in the past

* **If the customer defaults (y)** which's what we are trying to predict

### 5. Splitting Data

We divide the data into two parts:

* **Data to train the model** which we use to teach the model

* **Data to test the model** which we use to see how well the model works

Usually we use 80% of the data to train the model. 20% To test it.

### 6. Making Sure Everything is on the Same Scale

We make sure all the numbers are on the scale so the model can understand them better.

### 7. Training the Model

We use a ** Regression** model to train the machine learning model.

Logistic Regression is often used for problems where we are trying to predict one of two things like if a customer will default or not.

### 8. Checking How Well the Model Works

After training the model we check how well it works using some metrics:

* A table that shows what the model predicted and what actually happened

* A report that shows how well the model did

* A graph that shows how well the model can tell the difference between customers who will default and those who will not

These metrics help us see how accurate the model is.

---

## Machine Learning Methods

### Logistic Regression

Logistic Regression is an popular way to classify things. It predicts the probability that something will happen, like a customer defaulting.

### Decision Tree

Decision Tree models make predictions by splitting data into branches based on conditions. They are easy to understand and visualize.

### Random Forest

Random Forest is an advanced algorithm that builds many decision trees and combines their results. It usually gives results and reduces overfitting.

### Support Vector Machine (SVM)

SVM works by finding the boundary that separates different classes of data.

### K-Nearest Neighbors (KNN)

KNN predicts results based on the data points in the dataset.

---

## Tools and Libraries Used

This project uses the following Python libraries:

* Pandas to handle data

* NumPy to do numerical operations

* Matplotlib to visualize data

* Seaborn to visualize statistics

* Scikit-learn to build machine learning models

---

##

In this project we built a machine learning model to predict credit card default using customer data. We used Logistic Regression as the algorithm to classify whether a customer will default or not.

The results show that machine learning can help financial institutions analyze customer behavior and identify risks. This type of analysis can help banks make better decisions and reduce financial losses.

---

## Future Improvements

Some things we can do to improve the project in the future include:

* Using advanced models like Random Forest or Gradient Boosting

* Making the features better

* Handling class imbalance effectively

* Making a web application, with the model

---

## Author

This project was created as part of a machine learning learning project and is intended for purposes.
