# Predicted-purchase-intent-of-e-commerce-website-visitors-
## Abstract
The purpose of this project is to analyze the behavior of online shoppers through their click-stream data on an E-commerce platform, in order to Predict whether their visit to the website will result in a purchase(revenue generation). 

## Introduction
- The popularity of online shopping is growing, and e-commerce platforms need to improve sales by analyzing purchase patterns and customer psychology.
- Analyzing customer purchase history is an effective method for predicting purchasing intentions and gaining valuable insights into shopper behavior.
- Understanding customer behavior can help e-commerce businesses to optimize their tactics and enhance sales, such as by developing targeted marketing strategies and personalized promotions.
- Effective sales funnels can also be created by analyzing customer behavior and identifying potential bottlenecks.
- Accurate analysis systems of online purchase patterns can provide significant benefits for businesses in the e-commerce industry.

## Dataset
- The Dataset ’Online Shoppers Purchase Intention’ is taken from UCI Machine Learning Repository.
- There are 12,330 instances in the data. These instances are sessions of online users.
- Each session has 18 features out of which 10 are numerical and 8 are categorical.
- To predict the intention of customers we take ‘Revenue’ as the target variable. If the output is 1 then the customer purchases, else it is not a purchase.

## EDA

![image](https://github.com/hputta23/Predicted-purchase-intent-of-e-commerce-website-visitors-/assets/47238017/e72548d4-774a-427c-a610-17fb91ec800f)
- Highly Unbalanced Dataset: 
Eighty-five percent (10,422) of the 12,330 generated no income(Negative class samples). At the same time, the rest (1908) completed their shopping and generated revenue(Positive class samples).


![image](https://github.com/hputta23/Predicted-purchase-intent-of-e-commerce-website-visitors-/assets/47238017/b5da28a7-4989-4df0-b512-6e49d0d2bcdc)
- Correlation: The most highly correlated features among them are BounceRates and ExitRates, which show a correlation coefficient of 0.91. ProductRelated and ProductRelated_Duration with a correlation coefficient of 0.86.

![image](https://github.com/hputta23/Predicted-purchase-intent-of-e-commerce-website-visitors-/assets/47238017/af0316ce-f3dd-464f-8e8c-c3ffaf1fc6a4)
- Returning vs. New Visitors: Maximum number of customers return to website even though not many of them contributed to revenue generation.

