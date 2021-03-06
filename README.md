![IMG_20200304_203709 (1)](https://user-images.githubusercontent.com/72034856/130875598-302dffe1-3954-4039-845d-20844932cfee.png)

# INTRODUCTION
### My name is Raphael Abasiama and I have 2 years of internship and contract experience in data analytics/science. Proficient in data cleaning/ feature engineering, descriptive, prescriptive and predictive analysis.
##   SKILLS
#### DATABASE: 
MYSQL,
SQLITE,
MONGODB

#### DATA ANALYSIS: 
EXCEL,
POWERBI, 
NUMPY,
MATPLOTLIB,
SEABORN,
PLOTLY

#### MACHINE LEARNING AND DEEP LEARNING:
SKLEARN(Machine Learning),
KERAS(Deep Learning)

#### FRONTEND: 
HTML,
CSS,
BOOTSTRAP

#####  BACKEND:
FLASK
#
# DATA ANALYSIS PROJECTS

# [COVID19 DATA ANALYSIS](https://github.com/Raph-09/CORONAVIRUS-DATA-ANALYSIS-PowerBI-)

![covid_pg1](https://user-images.githubusercontent.com/72034856/153959826-29f0543c-b6b7-4166-b58e-ffb14497222e.PNG) 

![covid_pg2](https://user-images.githubusercontent.com/72034856/153959984-f154a829-2285-4e9d-b074-6d7f738d6c80.PNG)

### ETL(Data Cleaning)

1) Source of data is wikipedia--https://en.wikipedia.org/wiki/COVID-19_pandemic_by_country_and_territory
2) PowerBI web connector is used to pull the data into PowerBI
 
4) Data Transformation is carried out

    a) Remove the "total" rows

    b) Convert decimals into percentages

    c) Replace errors with zeros 

    d) Rename invalid column names with correct names
  
4)Close and Apply
  
### Data Visualization

1)Use Region as slicer to filter the data 

2)Proportion of covid patients that are dead and those that are still alive

3)Total cases by Region

4)Top 5 Regions with covid patients still living

5)Top 5 Regions with most covid death

6)Top10 Most vaccinated countries

7)Vaccination by Regions

###
#

# [CRYPTOCURRENCY MARKET ANALYSIS](https://github.com/Raph-09/Cryptocurrency-Market-Analysis)


![image](https://user-images.githubusercontent.com/72034856/158796822-96d1dea5-0f7f-4416-8af1-bf2495caa47d.png)


### Source of data 

The source of data is kaggle.com

### Data Analysis and Visualization

1)Top 10 cryptocurrencies by market values

2)Latest cryptocurrencies

3)Oldest cryptocurrencies

4)Top 10 cryptocurrencies by rank

5)Bitcoin price trend and moving averages

6)Etheruem price trend and moving averages

#
# DATA SCIENCE PROJECTS

# [MALL CUSTOMER SEGMENTATION ANALYSIS](https://github.com/Raph-09/Machine-Learning/blob/main/credit-card-fraud-detection-solution.ipynb)

![CLUSTERING](https://user-images.githubusercontent.com/72034856/158807176-1266efa2-4c77-4e64-a0a1-8c78f099446c.jpg)

This is a blog post in which I explain how to implement "mall customer segmentation" using clustering algorithms. The clustering algorithms I covered in the article are KMeans clustering and DBSCAN clustering. Silhouette coefficient was used to evaluate the performance of the clustering algorithms.  KMeans performed better than DBSCAN clustering.


### [Project2: Employee Salary Prediction(End to End)](https://github.com/Raph-09/Machine-Learning/blob/main/credit-card-fraud-detection-solution.ipynb)

### [LINK TO HEROKU APP](https://salary-app-1.herokuapp.com/)

The project aims to lessen the burden of Head of Recruitment(HR) by making it easier for the HR to predict the salary of an employee.
This project is an end to end project where I explored the data, engineered the features, test models and deployed the best model into the Flask app.
The following steps where followed;
1) Feature Engineering: missing values where handled
2) Exporatory data analysis: Explored the data for insight
4) Feature Scaling: Standard Scaler was used
5) Lasso regression Model  was used for predictive modelling
6) Save the model as a pickle file
7) Build Flask App and Deploy the App into heroku platform

### [Project1: Credit Card Fraud Detection (OVERVIEW)](https://github.com/Raph-09/Machine-Learning/blob/main/credit-card-fraud-detection-solution.ipynb)

This is a classification problem in which we aim to predict if a transaction is fraudulent. The dataset comprised 31 columns and 284807 records. The imbalanced nature of the dataset was fixed using a technique called oversampling.  Exploratory Data Analysis, Feature Selection, and Feature Scaling were performed, and important features were chosen to make the data ready for model building.
Below is the summary of the performance of each of the machine learning models:
Logistic Regression(accuracy-97% and recall- 94%),
Naive Bayes(accuracy-98 and recall-92%),
Decision Tree(accuracy-99% and recall-85%),
Hard-Voting-Classififer(accuracy-99% and recall-84%),
Soft-Voting-Classifier(accuracy-100% and recall-85%).

### [Project2: Drug Prediction (OVERVIEW)](https://github.com/Raph-09/Machine-Learning/blob/main/drug-classification-100-accuracy.ipynb)

The objective of this project is to predict the kind of drug a person should take, given the person's age, sex, BP, cholesterol levels,  and sodium content.
The dataset was explored, features were selected and scaled for the model to be built.
The following gives the summary of the models:
DECISION TREE-100% ACCURACY,
NAIVE BAYES-100% ACCURACY,
RANDOM FOREST-100% ACCURACY.

### [Project4: Employee Salary Prediction (OVERVIEW)](https://github.com/Raph-09/Machine-Learning/blob/main/employee-salary-prediction-r2-100.ipynb)
The goal of this project is to predict the salary of an employee,  given his or her blood group, age, eating habits,  and lifestyle.
EDA was performed, features selected, and the machine learning model gave r2 of 100%.

### [Project5: House Price Prediction (OVERVIEW)](https://github.com/Raph-09/Machine-Learning/blob/main/house-price-prediction.ipynb)

This is one of the most popular datasets in the machine learning community, in which we try to predict the price of a house in Boston.
The data has 81 columns and 1460 rows.
I explored the data, selected important features, and scaled it before feeding it into the models.
Below is the summary of models performance:
RANDOM FOREST (MAE=MAE: 5363.9,RMSE: 7627.95),
XGBOOST (MAE: 11110.25,RMSE: 14983.58).


### [Project6: Used Car Price Pridiction (OVERVIEW)](https://github.com/Raph-09/Machine-Learning/blob/main/vehicle-price-prediction-cardekho.ipynb)

The objective of this project is to predict the price of a used car,  given the car's showroom price, distance covered, year of purchase, mode of transmission, and fuel type.
The r2 of the models on the test set is given below:
R2 of voting regressor: 93%,
R2 of of random forest regressor: 93%,
R2 of knn_regression  is: 92,
R2 of of lasso_regression: 83.

### [Project7: Air Quality Prediction (OVERVIEW)](https://github.com/Raph-09/Deep-Learning/blob/main/ANN%20PROJECTS/(Ann)Air_Quality.ipynb)
This project aims to predict the air quality of an area by using pm2.5 as a factor that determines if the air is polluted.
The reason for using pm2.5 is because it is the most dangerous air pollutant.
The models were built using temperature, Maximum temperature, Minimum temperature, Station Level pressure, Humidity, wind, and visibility.
The artificial neural network gave the mean absolute error as  31 PM2.5 and the root means squared error as  50 PM2.5.

### [Project9: Bank Customer Churn  (OVERVIEW)](https://github.com/Raph-09/Deep-Learning/blob/main/ANN%20PROJECTS/(Ann)_customer_churn_prediction.ipynb)
Banks need to know beforehand if a customer wants to quit the bank. This will help them to target the individual(s) with ads to lure them into staying.
This machine learning project tries to ensure that it uses the customer's credit score,  geography, gender, age, tenure, account balance, if he/she has a credit card, and if the person Is an active member of the bank.
The artificial neural network gave an accuracy score of 80 % on the testing dataset.

### [Project10: Sentiment Analysis (OVERVIEW)](https://github.com/Raph-09/NLP/blob/main/stock_sentiment_analysis.ipynb)
The stock market is a huge market that has made many millionaires. Therefore, it is important to study the sentiment of the news headlines to understand the value of a company.
This project tries to predict the stock price given 25 news headlines of a given company.
The models(Random Forest and Naive Bayes) gave an accuracy score of 70%.

### [Project11:Fake News Detection](https://github.com/Raph-09/Deep-Learning/blob/main/RNN_LSTM/(LSTM)_Fake_News_Prediction_.ipynb)

We live in a world with lots of fake news articles, and the internet helps to spread them even faster. If we can find a way to capture these fake news articles on time, it will save many folks. This is the motivation behind this project,  in which I predicted if the news is fake by using the title.
The LSTM model gave an accuracy of 92%.

### [BlogPost:Mall Customer Segmentation Project Using Clustering Algorithms](https://akpan1653.medium.com/mall-customer-segmentation-project-using-clustering-algorithms-d459d31135ae?source=friends_link&sk=a6c5b2600d15b0b473d27939b27a422c)
This is a blog post in which I explain how to implement "mall customer segmentation" using clustering algorithms. The clustering algorithms I covered in the article are KMeans clustering and DBSCAN clustering. Silhouette coefficient was used to evaluate the performance of the clustering algorithms.  KMeans performed better than DBSCAN clustering.
