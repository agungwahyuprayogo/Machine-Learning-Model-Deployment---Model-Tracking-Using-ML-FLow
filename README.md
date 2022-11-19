# Machine Learning Model-Deployment
# Model Tracking Using ML FLow
mini project by Group 1 Data Science B - MyEduSolve

# Use Case
* **Use Case Summary**


* **Objective Statement** :
    
    * Get business insight about the average, maximum and minimum minimum visitor and buyer
    * Get business insight about how many visitor in 30 day
    * Get business insight about how many buyer in 30 day
    * Get business insight about how many visitors buy more than once
    * Get business insight about how to predict buyers based on visitors in one day using Machine Learning Simple Linear Regression
    * Deployment using ML Flow
    
    
* **Challanges** :
    * Do not know the time of data collection
    * Don't know what the opening and closing hours are


* **Methodology / Analytic Technique** :
    * Descriptive analysis
        * Describe the information such as, min/max value of each column, average, and the total count 
    * Graph analysis
    * Using Machine Learning to predict 
        * Using Simple Linear Regression
    * Using ML Flow to Deployment


* **Business Benefit**:

    * Gain insight to treat and keep customers based on segment
    * Gain insight to improve the quality of company services so that customers remain loyal and gain more profit for the company
    * Build machine learning using Simple Linear Regression
    * Deployment using MLFlow


* **Expected Outcome**:

    * Know about the average, maximum and minimum minimum visitor and buyer
    * Know how many visitor in 30 day?
    * Know how many buyer in 30 day?
    * know how many visitors buy more than once?
    * Know how to predict total buyers based on visitors in one day using Machine Learning Simple Linear Regression ?
    * Know how to Deployment using MLFlow?

# Business Understanding
* Data is a sales data in supermarkets based on visitors and buyers within 30 days:
    * How about the average, maximum and minimum minimum visitor and buyer
    * How many visitor in 30 day?
    * How many buyer in 30 day?
    * How many visitors buy more than once?
    * How to predict buyers based on visitors in one day using Machine Learning Simple Linear Regression?
    * How to Deployment using ML Flow?
    
# Data Preparation

* **Code use** :
    * Python 3.9.13
* **Package** : 
    * Pandas, Numpy, Matplotlib, Seaborn, Scipy, Sklearn, and Warning 
    
# Data Cleansing

the data is clean **because there are no missing values and the data types are appropriate** so **no need for data cleansing**

# Exploratory Data Analysis

In statistics, exploratory data analysis is the approach of analyzing a data set to summarize its main characteristics, often using statistical charts and other data visualization methods

* **Average, maximum and minimum minimum visitor and buyer**

![1 describe](https://user-images.githubusercontent.com/101789879/202834553-ab1ee81b-fc30-4f7e-9569-2ab81b319c8a.jpg)

From the results of a descriptive analysis using 30 rows of data, some insights were obtained. The distribution of the data is still normal, this can be seen from the small standard deviation. **On average** buyers are 35 visitors with 33 purchases.**In busy times** , the maximum number of visitors is 42 visitors with **the most purchases** are 38. **The quietest visitors** are 29 visitors and **the minimum buyer** is 29 so that **it can be concluded that most likely when it is quiet every visitor buys 1 goods**. When there were 38 visitors, the average purchase was 36. When there were 35 visitors, the average buyer was 33. When there were 32 visitors, the average buyer was 31.

* **How many visitor in 30 day**

![2 how many visitors](https://user-images.githubusercontent.com/101789879/202834603-bd915bca-c166-46ee-af8d-e7dd4a15e4b4.jpg)

From visitor data in the last month, **the most frequent** (4 days) visitors came to the supermarket **as many as 40 and 36 visitors**. this might happen because **weekends** in one month can happen 4 times (Saturdays and Sundays). **the loneliest day** happened when one day only had **29 visitors**, fortunately it only happened for 1 day. **possibly** there will be no visitors because it falls on **Monday and it's raining**

* **How many buyers in 30 day**

![3 how many buyers](https://user-images.githubusercontent.com/101789879/202834711-59e55568-3ca9-4e8e-b9da-37c76d3e64bd.jpg)

from the last month's data, most often (**6 days**) there are **32 buyers in one day**. it might happen because it coincides with **weekend and there is a promotion**. and **the loneliest** day of buyers occurred where there were only **29 buyers in one day.**

* **How many visitors buy more than once**

![3 visitors who buy more than one time](https://user-images.githubusercontent.com/101789879/202834742-4b18def7-1611-44bd-8383-29f5ef4b9e55.jpg)

can be seen here, the possibility of a visitor coming in one day to buy **more than one item is 26%**. this might happen because **visitor's friends / family ask to buy the same item as the visitor**

* **Predict buyers based on visitors in one day using Machine Learning Simple Linear Regression**

