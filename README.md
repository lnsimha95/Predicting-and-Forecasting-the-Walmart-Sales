# Predicting-and-Forecasting-the-Walmart-Sales
This project uses prediction and forecasting algorithms to analyze the Walmart sales dataset.


# Detailed Problem that Walmart faces

One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. There are certain events and holidays which impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock some times, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.

Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data. Historical sales data for 45 Walmart stores located in different regions are available.

# Shorter and Concise Problem statement


To analyse and predict the demand for 45 Walmart Stories so that it can plan its promotional strategies and markdowns during holiday and non-holiday weeks


# Methodology 

I used numerous prediction algorithms for predicting the Walmart sales like Linear regression, random forest regression, Lasso regression, ridge regression, Simple Gradient boosting regression and XG Boosting regression. And I used Holt Winters Exponential Smoothing time series model to forecast the Walmart Sales as it is a retail dataset that is bound to seasonality. 


# Data Source link 

https://www.kaggle.com/datasets/yasserh/walmart-dataset 




# Insights Obtained


# 1.  Which was the month with the highest sales?

April is the month with the highest Sales 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/07094aaa-49e9-4e92-855b-c575686f8797)

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/f811bce7-266f-4109-99a0-c86bd448e35f)


# 2. Which day had the highest Sales for Walmart in a week? 

Thursdays was the day with highest sales in a week for Walmart. 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/de2a9f3c-de02-4283-addf-42f571c553a7)

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/9d2dd2ad-6f14-4550-a6b5-5b520bed4123)


# 3. Which year contributed to the highest Sales in Walmart? 

2011 contributed to the highest sales in Walmart. 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/8b53b94e-c72b-4bd4-80c1-67873813801c)

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/5b85b1ef-446d-4171-badd-76499878c673)



# 4. Which week had the highest Sales: Holiday or Non -holiday week?

Obviously, non - holiday weeks contributed to the highest sales as there are 9 months that come under non - holiday weeks. 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/66065805-99c4-4028-8a3c-bb28bff54796)


# 5. Which Stores performed the best and least in terms of their total sales on a monthly, weekly, and yearly basis? 


![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/eb97af7a-51b5-4bfa-b17d-ce705fef9f7f)


# 6. Correlation Matrix for all features 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/bc452588-ea43-4950-bbb0-0e6f3ab8f961)

#### 1. We can see that store and unemployment have some amount of correlation of 0.26
#### 2. Temperature and fuel price have only 0.14 correlation Whereas, temperature and CPI has a lesser correlation of 0.18.So, there is lesser possibility of multicollinearity from this above correlation 
#### 3. We don't take the year and fuel price into concern as year is a constant variable with only three unique values


# 7. Feature Importance of the best model obtained best on the R2-square in test and least RMSE value than the actual y - values 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/2d970894-824d-4ec3-a6df-6cda52d35184)


# 8. Evaluation metrics: Regression problem (3 Algorithms mentioned, but tried more than 5)

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/c0893c33-c154-4179-922a-8e8a137a821e)


# 9. Evaluation metrics paramater - Time series forecasting (Holt Winters Exponential Smoothing Model) 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/a5704225-19ff-4dd0-bcf9-da75d2f1c9b4)


# 10. Holt - Winters Exponential Smoothing model Predictions 

![image](https://github.com/lnsimha95/Predicting-and-Forecasting-the-Walmart-Sales/assets/109967940/bb67e959-2bdd-420c-947e-82c4aad28bf7)


# 11. Findings and Recommendations

1. As Thursday is the highest in terms of day-based sales, Thursday is the best day in the week for providing added discounts and promotions

2. With April topping in sales of all stores, April is the best month for providing any discounts or coupons. Not just during April, during July, October, and December, Walmart needs to stock items as there might be a rise in demand during these times. Also, there is a fall in Walmart sales during June, August, November and January. These are the times when the stock needs to be kept lesser as the sales might fall. 

3. 41st week that is first and second week of October is the best time for any weekly discounts offered to customers. Also, Walmart needs to stock more during this time as it is the start of Holiday season sales like Single's day. 

4. 2011 had the highest sales among all the three years

5. As most sales occur during the non-holiday weeks, Walmart must keep its stock reserved for these times than the holiday week

6. Ensure that these best performing stores doesn't run out of stock as they consistently perform on a yearly, weekly, monthly and daily basis. Also, most importantly, it is necessary to provide a basket of items for some discount to encourage sales. 

7. These stores didn't get enough public attention or footfall traffic for transactions 

8. So, it is better to minimize the stocks in these stores and focus on getting more transactions in this area and then maximize the stock keeping units (SKU) accordingly

9. Trying omnichannel sales can be another way or Walmart can change these regions into cloud stores like how it did during COVID-19 pandemic

10. Integrating some of these stores in the region where customers from two different areas can travel and get back to their homes quickly. So, they can utilize network optimization to place their shops near densely populated customer regions. 










