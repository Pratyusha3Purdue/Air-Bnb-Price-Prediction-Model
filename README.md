# Decoding COVID-19's Impact on AirBnb Price Patterns using Predictive Analytics

Problem Statement: To Unvcoer the impacts of Covid-19 Airbnb

Dataset Overview:

The dataset includes AirBnb data from two cities, New York and Chicago. The data is from 2010 till 2024, Covering the timeperiod before during and after Covid.

Methodology:

1. Cleaning the data:
  • We removed the $ symbol and any commas to make price a float data type and easy to make calculations on.
  • Dropped un-necessary columns like bedrooms for ease of working
  • Remove extreme outliers
  • Classified the data entries as Before , During Covid or After based on: 
      if they were recorded before Dec 2019 : Before || between Dec 2019 and Dec 2021 : During Covid || after 2021 : After

3. EDA:
  • To find the number of Unique hosts and Unique listings 
  • Listings Count by Room Type and Property type
  • Plot categorical variables and numerical variables
  • Visualized relationships between prices and key features: room type, property type, number of beds, and accommodates
  • Plotted price trends over time, focusing on the COVID-19 periods.
  • Analyzed review comments of the 1,000 most expensive listings to find commonly used terms.

4. Data Pre-Processing:
  • Handled missing values
  • Convert categorical variables to numerical using Label Encoding
  • Split the data into features and target
  • Split the data into training and testing sets (70-30 split)
6. Model Building:
 • Used LightGBM for model training and prediction.
 • Performed cross-validation to evaluate model performance.
 • Tuned hyperparameters using grid search.
 • Predicted Prices
 • Evaluated feature importance to understand the key drivers of price changes.
 7. Evaluate reults:
 • Compared actual vs. predicted prices on both training and test datasets to assess model accuracy.
   


<img width="757" alt="image" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction-Model/assets/141969918/d49057d6-024e-4738-b995-e19231e767ee">


<img width="536" alt="Screenshot 2024-05-17 072822" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction/assets/141969918/a0c0ca83-1aa6-44b1-80f5-bba56fb01d8d">

<img width="532" alt="Screenshot 2024-05-17 072315" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction/assets/141969918/0a6a17d8-8c77-434d-beb3-b85a87c13e2a">


<img width="536" alt="Screenshot 2024-05-17 072923" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction/assets/141969918/e572975d-b641-438d-9803-71f76ddd7d29">


<img width="540" alt="Screenshot 2024-05-17 073018" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction/assets/141969918/19baa705-1159-4de4-9607-57e3a0abca0d">


<img width="545" alt="Screenshot 2024-05-17 073002" src="https://github.com/Pratyusha3Purdue/Air-Bnb-Price-Prediction/assets/141969918/2a47c5eb-e182-4b11-a2ff-d0519db29f89">
