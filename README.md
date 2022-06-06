# Supervised-and-Unsupervised-Learning
The R-pubs link for the two files are:
 https://rpubs.com/marysofteng/911313 and https://rpubs.com/marysofteng/911340 
 
 For the supervised model, the modeling is done using decision tree to predict the chances of one to click on the ad while he or she is browsing.
 For the unsupervised learning, the model is developed using kmeans clustering and Hierachichal clustering to group the type of customers in terms of revenue generation.
 ## language used
 
 R-Programming
 ## Technology used

R-Markdown

## Licence

This project it is only used for learning purposes

## How to run it

Download it and open it using R studio and you will be able to run it.
 ## Major Libraries used

- library(ggplot2)
- library(ggvis)
- library(Amelia)
- library(tibble)
- library(dplyr)
- library(ggplot2)
- library(Hmisc)
- library(reshape2)
- library(caret)
- library(superml)
- library(tidyverse) # data manipulation
-library(corrplot)
- library(gridExtra)
- library(GGally)
- library(cluster) # clustering algorithms 
- library(factoextra)

## Flow of Activities

- Problem Definition
- Data Sourcing
- Check the Data
- Perform Data Cleaning
- Perform Exploratory Data Analysis  (Univariate, Bivariate & Multivariate)
- Modeling (Supervised and supervised Learning)
- Implement the Solution

## Description of the datasets
1. http://bit.ly/EcommerceCustomersDataset 
- The dataset consists of 10 numerical and 8 categorical attributes. 
- The 'Revenue' attribute can be used as the class label.
- "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" 
- represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.
The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action,
e.g. moving from one page to another. 
- The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
- The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and
 then leave ("bounce") without triggering any other requests to the analytics server during that session. 
- The value of the "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.
- The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 
- The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) 
in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering 
the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, 
this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, 
and its maximum value of 1 on February 8. 
- The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.
2. http://bit.ly/IPAdvertisingData 
