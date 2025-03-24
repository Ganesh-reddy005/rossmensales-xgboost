# Rossmensales using XGBoost
Using a dataset from kaggel named Rossmensales. i have created a predictive model which predicts 'Sales' for the given test data.
I have done EDA to find out trends and patterns from the data and found out usefull insights. I have also done 'Feature Engineering' on certain columns so that models learn better, such as OneHotEncoder etc are used.
Scaling of Features is also done to bring data to a range of(0-1) using MinMaxScaler.
## Models used
I have used Decision Tree ,but it had issue of over fitting with training data.
Had better results after using Randomforest and , tunning its parameters such as max_depth, n_estimators etc.
Finally i have used XGBoost from best accuracy and tuned its hyperparameters - model=XGBRegressor(n_estimators=400,max_depth=7,learning_rate=0.3,random_state=42)
