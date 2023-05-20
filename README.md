# Sales-Forecasting-Using-Facebook-Prophet
This is a data science project to forecast sales in the future based on historical data from 1115 stores in a retail chain.
## Dataset (Rossmann Store Data)
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.<br>
Link:- https://www.kaggle.com/c/rossmann-store-sales/data
## Introduction
* For companies to become competitive and increase their growth, they need to leverage AI to develop predictive models to forecast sales in the future.
* Predictive models are used to forecast future sales based on historical data while taking into account seasonality effects, demand, holidays, promotions, and competition.
* In this project the sales team has collected data related to various factors from 1115 stores and the objective is to predict the future sales based on these features.
## Feature Variables 
* Id:- transaction ID (combination of Store and date)
* Store:- unique store Id
* Sales:- sales/day, this is the target variable 
* Customers:- number of customers on a given day
* Open:- Boolean to say whether a store is open or closed (0 = closed, 1 = open)
* Promo:- describes if store is running a promo on that day or not
* StateHoliday:- indicate which state holiday (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
* SchoolHoliday:- indicates if the (Store, Date) was affected by the closure of public schools
* StoreType:- categorical variable to indicate type of store (a,b,c,d)
* Assortment:- a = basic, b = extra, c = extended
* CompetitionDistance(metres):- distance to closest competitior store
* CompetitionOpenSince[Month/Year]:- date when competition was open
* Promo2: Promo2 is a continuing and consecutive promotion for some stores (0 = store is not participating, 1 = store is participating)
* Promo2Since [Year/Week]: date when the store started participating in Promo2
* PromoInterval: describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

## Steps Involved
* Importing the Libraries and the Dataset
* Exploratory Data Analysis and Data Preparation
* Model Building
## Output
### Sales Forecast when Holidays are excluded
![image](https://github.com/sahilfaizal01/Sales-Forecasting-Using-Facebook-Prophet/assets/106440078/69da4eba-3178-49a3-a8d2-20ee9f05cb7a)

### Sales Forecast when Holidays are included
![image](https://github.com/sahilfaizal01/Sales-Forecasting-Using-Facebook-Prophet/assets/106440078/a8b434b5-ca91-4b46-9abc-6718339b351b)

