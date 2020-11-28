Project 3
Sales Department
** Hi! Everyone Well come to this new case study for companies to become competative and Skyrocket their Growth and Sales.

They need to leverage Artificial and Machine learning to develop a predctive modesl so they can be able to forecast Sales in the furture.

Predictive models attampt at forecasting furture Sales based on historical data while taking into accounts. Seasonality affects and demand holidays promptions and competition.

In this Project we work as a data scientist in the Sales department and the Sales team provided you with data from eleven hundred stores.

The objective is to predctive furture daily Sales based on some features such as Stores promotions Store, Size school and state holidays, Distance away from compition and what type of products do therese stores carry.

In this case study we are going to learn many Skills.

Here are the main learning out comes:

Understand how to leverage the Power of data Science to predict furture product Sales.

Understand the theory and intuition behind time Series forecasting models.

Understand the thorey behind Facebook prophet time series forcasting tool.

Understand the concept of additive regression

List the adventages of Facebook Prophet.

Apply Facebook Prophet to Predict future Sales using VR real wordl dataset.

Predict furture Weekly, Montly and Yearly trends.

Let's get started

Task#1:UNDERSTAND THE PROBLEM STATEMENT AND BUSINESS CASE

INPUTS AND EXPECTED OUTPUTS
Id: Transaction ID (Combination of Store and Data).
Store: Unique store id
Sales: Sales/Day, this is the target variable.
Customers: number of customers on a given day
Open: Boolean to day wheather a store is open or closed( 0 = closed, 1 = open)
Promo: Describe if store is running a promot on that day or not.
StateHoliday: Indicate which state holiday(a = public holiday, b = Easter holiday, c = Christmas, 0 = None).
SchoolHoliday: Indicate if the (Store, Date) was affected by the closure of public schools.
StoreType: Categorical variables to indicates type of store(a, b, c, d)
Assortment: a = basic, b = extra, c= extended (Based on the size and location of the store)
CompetitionDistance(meters): Distance to closest competitor store.
CompetionOpenSince[Month/Year]: Data When competion was open.
Promo2: Promo2 is a continuing and consecutive promotion for Some stores (0 = Store is not participating, 1 = Store is participating).
Promo2 Since[Year/Week]: Date when store started participating in Promo2
PromoInterval: Describe the consuecutive intervals, Promo2 is started, naming the months promotion is started a new
E.g: "Feb, May, Aug, Nov" means each round starts in February, May, August, November of any given year for that store.


Task#2.2: IMPORT STORE INFORMATION

Explore Store Data
Store: Store Unique ID,
StoreType: Categorical variable to indicate type of store (a, b, c, d)
Assortment: Describes an assortment level(a = basic, b = extra, c = extended)
CompetitionDistance:Distance to closest competition store
CompetitionOpenSince[Month/Year]: Provides an estimate fo the date When competion was open.
Promo2: Promo2 is a continuing and consecutive promotion for some stores (0 = Store is not participating, 1 = Store is participating)
Promo2Since[Week/Year]: Date when the store started participating in Promo2
PromoInterval:Describe the consecutive intervals Promo2 is started, naming the months the promotion is started a new
E.g Feb, May, Aug, Nov" means


Task#3: EXPLORE BOTH SALES AND TRAINING DATASETS


Task#3.1: EXPLORE SALES TRAIN DATA


Task#3.2 EXPLORE STORES INFORMATION DATA


Task#3.3 EXPLORE MERGED DATASET

Task#4 UNDERSTAND THE INTUITION BEHIND FACEBOOK PROPHET

FACEBOOK PROPHET
Prophet is open soruce software released by Facebook's core Data Science team
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with Yearly, Weekly and Daily seasonality, plus holiday effects.
Prophet works best with time series that have strong seasonal effects and Serveral Seasons of historical data.



Facebook Prophet implements an additive regression model with four elements:
A piecewise linear, Prophet automatically picks up change points in the data and Identifies any changes in trends.
A yearly seasonal component modeled using Fourier Series.
A weekly seasonal component.
A holiday list that can be manually provided.
Additive Regression modle takes the form:


FACEBOOK PROPHET BENEFITS
ACCURATE AND FAST

Facebook teams uses prohpet for accurate forecasting and planning.
Prophet can generate results in seconds automatic.
No need to perform data processing
Prophet works with missing data with serveral outliners.
Domain Knowledge Integration

Users can tweak forecast by manually adding domain specific knowledge.


Task#5: TRAIN THE MODEL PART A

Task#6 TRAIN THE MODEL PART B

StateHoliday: Indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are clsoed on public holidays and weekends (a = public holiday, b = Easter Holidays, C = Christmas, 0 = None)

SchoolHoliday: Indicates if the (Store, Date) was affected by the closure of public schools.


Code and Resources Used:

Python Version: 3.7 Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle Sources: https://towardsdatascience.com/confusion-matrix-for-your-multi-class-machine-learning-model-ff9aa3bf7826

https://opendatascience.com/how-does-the-random-forest-algorithm-work-in-machine-learning/

Google Colab

https://towardsdatascience.com/

https://www.udemy.com/


