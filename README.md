# Flight_Price_Prediction

### Project Name: Flight Price Prediction
The main aim of this project is to predict the flight price based on various features. 

### Lifecycle of this project

### •	Data Collection

For this project collected data from the Kaggle.
Dataset to downloaded from the below link

https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/

### •	Exploring data and handling the missing values

Explore basic information like how many row and column, data type of each feature and handling the missing values by either removing them or imputing them with relevant data.
### •	Feature Engineering

Select each feature and convert data into different format as per requirements. The most meaningful techniques of feature engineering are used to transform data into a form where a model can understand better and dealing with data and pattern anomalies.

### •	Feature Selection

After transforming the data to the right format most of the time especially with a high dimensional dataset, we end up with many features, we cannot feed all the features to the machine learning model, that is not how it works, that would over fit the model hugely. Instead, we have to choose the right number of features. I implemented **Lasso regression - Lasso regression will select only those features that are useful, discard the useless or redundant features. In Lasso regression, discarding a feature will make its coefficient = 0.

To Indentify **Multicollinearity** I used **Variance Inflation Factor- VIF. It provides score if the VIF score is greater than 5 it indicates that the independent features are highly correlated to each other.

### •	Model Building

This step includes choosing the appropriate type of model, whether the problem is a classification problem, or a regression problem or a clustering problem. After choosing the model, amongst the various algorithms present. We need to tune the hyper parameters of each model to achieve the desired performance. **Implanted various regression model like: Liner Regression, Decision Tree, Randomforest Regressor and achieved R² score 0.823 with RandomForestRegressor(). 


 
