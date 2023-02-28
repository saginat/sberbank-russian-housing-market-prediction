# House Market Prediction using Sberbank Dataset
This repository contains the code and resources for a machine learning project that predicts house prices using the Sberbank dataset from Kaggle. The project is implemented in Python using Jupyter Notebook.

## Dataset
The Sberbank dataset contains information on real estate transactions in Russia, including data on house prices, property features, and macroeconomic indicators. The dataset includes over 300 features, such as the number of rooms, the distance to the nearest metro station, and the availability of amenities such as schools and hospitals.

https://www.kaggle.com/competitions/sberbank-russian-housing-market

## Steps
### EDA
The first step of the project was to perform exploratory data analysis (EDA) on the Sberbank dataset. This involved examining the data for missing values, outliers, and other anomalies, as well as identifying correlations between different features. The EDA was done using Python packages such as Pandas, Matplotlib, and Seaborn.

### Visualization
After the initial EDA, the next step was to create visualizations of the data to gain further insights. This included creating scatter plots, histograms, and other types of plots to visualize the distribution of the data and identify patterns and trends.

### Preprocessing
The next step was to preprocess the data to prepare it for use in the machine learning models. This involved filling in missing values, scaling the data, and encoding categorical features. We used various techniques such as imputation, one-hot encoding, and label encoding to preprocess the data.

### Feature Engineering
Once the data was preprocessed, we performed feature engineering to create new features that might improve the performance of the models. This involved creating interaction terms, polynomial features, and other transformations of the existing features.

### Model Testing
The next step was to train and test several machine learning models on the preprocessed and engineered data. We used a variety of algorithms, including linear regression, decision trees, random forests, and gradient boosting, and evaluated their performance using metrics such as mean squared error (MSE) and R-squared.

### Error Testing
Finally, we performed error testing to identify the sources of error in the models and improve their performance. This involved analyzing the residuals, identifying outliers and influential points, and experimenting with different modeling techniques and hyperparameters.

## Conclusion
This project demonstrates the use of machine learning techniques to predict house prices using the Sberbank dataset from Kaggle. By performing EDA, visualization, preprocessing, feature engineering, model testing, and error testing, we were able to create models that accurately predict house prices and identify the sources of error in the models.
