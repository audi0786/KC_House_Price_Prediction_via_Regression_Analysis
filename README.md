# House Prices Prediction - via Linear Regression 

Author - Udhai Pratap Singh

For detailed analysis in jupyter notebook, please refer: https://github.com/audi0786/dsc-phase-2-project.git


![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-2-project-campus/master/halfway-there.gif)


## Project Overview

This project analyzes the house prices in King County, WA, USA. The analysis ails to guide a real estate agency is advising their clients
on the right price for house sale or purchase, as well as impact of renovation on house prices. 

### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder. As you will notice that some of the column names are somewhat ambigious and for further reference you can go to the original source of the data at: (https://geodacenter.github.io/data-and-lab/KingCounty-HouseSales2015/)



### Business Problem

Prime House Agency is a renowned real estate agency active in the King County and they want help in giving prospective clients advice 
on houses prices in the area. They are looking for insights in which houses are overpriced/underpriced and what is the impact of factors 
like waterfront, view and renovations on a house price. 



### Methods

In order to provide advice on the factors influencing the house prices, I have performed Multiple Linear Regression of this dataset. 

The main steps in my analysis of this project are as follows:
1. Data cleaning - involving data check, null values, dtypes as well as referring to the original source of data. 
2. Feature engineering - where we added a few new features relevant to our business problem like some features like Time_since_renovation 
create via linear operations on existing features. We also created polynomial features of the top 3 most important features. 
Also includes features scaling, normalizing, and splitting data in continuous, discrete, categorical features. 

3. Baseline Model - performed linear regression on a baseline model involving 

4. Multiple model - here we take an iterative approach to which features to keep based on key metrics like r2_test, mse_test, and adj R2_train. 

5. Top 10 most important features - using Recursive feature elimination from sklearn and performing Linear Regression on data we choose 10 features and explain its relevance to Prime Real estate agency in context of our business problem of helping the customers in buying or selling the houses at the right price. 



### Final model 

We took an iterative approach to find the best features which will help us solve our business problem. 
See regresssion analysis results of various iterations:

![awesome](https://github.com/audi0786/dsc-phase-2-project/blob/main/images/results%20of%2011%20iterations.jpg)















## Top features for predicting house prices:





## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!



##  More Information
See the full analysis in the Jupyter Notebookat https://github.com/audi0786/dsc-phase-2-project.git

For additional info, please contact Udhai P Singh at singhudhai16@gmail.com.

Repository Structure
This repo has only one master branch.


├── .ipynb_checkpoints
├── Data
├── CONTRIBUTING.md
├── images
├── 
├── 
├── LICENCE.md
├── King_County_House_Prices_Prediction.ipynb
└── Presentation.pdf
├── README.md
├── notebook.pdf

