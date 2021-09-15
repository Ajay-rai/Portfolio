# [Project 1: Used Car Price Estimator](https://github.com/Ajay-rai/used_car_price_predictor)
## Project Overview
* Created a tool that estimates price of a used car(MAE ~ $4K) to help the buyer negotiate while shopping and individuals who want to list their car on platforms like Facebook Marketplace.
* Scraped over 2000 car listings in California and NewYork from cargurus.com (listing website of used car) using selenium.
* Cleaned data and engineered features (such as model, built year, mileage, details, and description) from raw data.
* Performed EDA (exploratory data analysis) to handle missing values, remove outliers, transform variables, check correlation and shortlist variables for machine learning model building.
* Optimized Linear, Lasso, Ridge, Random Forest, and XGBoost regressors using GridsearchCV to find the best model.
* Deployed in Heroku cloud using Flask API endpoint. Made it available online for users to get an approximate price of the car. [Link Here](https://carpricechecker.herokuapp.com/).

![alt text](/images/price_histogram.png)

The average price of used cars is around $20,000. And the distribution is left-skewed with some expensive cars worth almost $80,000.

![alt text](/images/feature.png)

Features such as mileage, age of car(built year) and gas mileage plays an important role in determining the price of used car.

![alt text](/images/deployment.png)

The deployment page looks like this. To use the price estimator, use this [link](https://carpricechecker.herokuapp.com/).

# [Project 2: BERT-NLP-TweetSentimentClassification](https://github.com/Ajay-rai/BERT-NLP-TweetSentimentClassification)
## Project Overview
* Determined the sentiment of public towards work from home by analyzing tweets.
* Scraped over 7000,000 tweets using snscrape. Performed text-preprocessing and EDA.
* Used AWS sagemaker/kaggle to get the sentiment from a pre-trained model based on DistillBert.
* Imported the pipeline from Hugging Face model hub.

![alt text](/images/Wordstweets.png)

Average word count of tweets is around 10 to 20.

![alt text](/images/pnn.png)

The sentiment of public was almost equally divided for 'work from home' trend. This could mean that 50% of public enjoy working from home while others like to go to office to do their work. This trend can change with time as more people now enjoy working from home.

![alt text](/images/hashtags.png)

Wordcloud of hashtags.

# [Project 3: FailurePrediction-NasaTurbofan](https://github.com/Ajay-rai/FailurePrediction-NasaTurbofan)
## Project Overview
* Predicted the remaining useful life (RUL) of turbofan based on sensor information using regression and deep learning models.
* Performed EDA on FD001 dataset. Removed unnecessary sensors and setting conditions.
* Fitted base model of linear regression. Also fitted random forest, xg_boost and time series models.
* Fitted deep learning models- MLP, LSTM.
* Calculated feature importance using SHAP values.

![alt text](/images/sensor14.png)

The sensor 14 value plotted against the target variable 'RUL'. As can be seen in the graph the sensor value deviates as RUL decreases.

![alt text](/images/modelperformance.png)

LSTM performed the best with 11.3% improvement from base model, linear regression.

![alt text](/images/comparision.png)

Predicted values plotted against the actual remaining life of turbofans. This is for LSTM model. The model predicts quite well for low RUL which is of more importance.

![alt text](/images/shap.png)

The feature importance was evaluated using shap values for XGBoost model.
