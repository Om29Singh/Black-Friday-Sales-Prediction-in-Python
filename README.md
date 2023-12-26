Customer Purchase Behavior Prediction

This repository contains a project aimed at understanding and predicting customer purchase behavior for "ABC Private Limited", a retail company. The company is interested in the purchase amount against various products of different categories.



Dataset : 
The dataset includes purchase summaries of various customers for selected high-volume products from the previous month. It also contains customer demographics such as age, gender, marital status, city type, stay in the current city, product details (product id and product category), and the total purchase amount from last month.



Objective : 
The goal is to build a model to predict customers' purchase amounts against various products, which will assist the company in creating personalized offers for customers against different products.



Tasks : 
The main task involves performing Univariate and Bivariate Analysis with respect to the Purchase. The 'purchase' column is the Target Variable.



Data Preprocessing : 
Data preprocessing will include checking the basic statistics of the dataset, checking for missing and unique values, performing Exploratory Data Analysis (EDA), checking for outliers, performing analysis by gender, marital status, occupation, city, age group, etc. Unnecessary fields will be dropped, categorical data will be converted into integers using a map function, missing values will be treated, columns will be renamed, and NaN values will be filled. Range variables will also be mapped into integers.



Data Visualisation : 
The visualisation part will involve creating plots for individual columns, age vs. purchase, occupation vs. purchase, product category vs. purchase, and city category via a pie chart. More possible plots will be explored as well.
