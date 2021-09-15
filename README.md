# Ajay's Portfolio
Data Science Portfolio

# Project 1: Used Car Price Estimator
## Project Overview
* Created a tool that estimates price of a used car(MAE ~ $4K) to help the buyer negotiate while shopping and individuals who want to list their car on platforms like Facebook Marketplace.
* Scraped over 2000 car listings in California and NewYork from cargurus.com (listing website of used car) using selenium.
* Cleaned data and engineered features (such as model, built year, mileage, details, and description) from raw data.
* Performed EDA (exploratory data analysis) to handle missing values, remove outliers, transform variables, check correlation and shortlist variables for machine learning model building.
* Optimized Linear, Lasso, Ridge, Random Forest, and XGBoost regressors using GridsearchCV to find the best model.
* Deployed in Heroku cloud using Flask API endpoint. Made it available online for users to get an approximate price of the car. [Link](https://carpricechecker.herokuapp.com/)

# Project 2: BERT-NLP-TweetSentimentClassification
## Project Overview
* Determined the sentiment of public towards work from home by analyzing tweets.
* Scraped over 7000,000 tweets using snscrape. Performed text-preprocessing and EDA.
* Used AWS sagemaker/kaggle to get the sentiment from a pre-trained model based on DistillBert.
* Imported the pipeline from Hugging Face model hub.

# Project 3: FailurePrediction-NasaTurbofan
## Project Overview
* Predicted the remaining useful life of turbofan based on sensor information using regression and deep learning models.
* Performed EDA on FD001 dataset. Removed unnecessary sensors and setting conditions.
* Fitted base model of linear regression. Also fitted random forest, xg_boost and time series models.
* Fitted deep learning models- MLP, LSTM.
* Calculated feature importance using SHAP values.
