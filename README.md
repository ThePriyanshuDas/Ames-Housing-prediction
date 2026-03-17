# Ames-Housing-prediction
This project predicts house prices using the Ames Housing dataset. It includes EDA, data cleaning, feature encoding, scaling, and a Linear Regression model. Performance is evaluated using MAE, MSE, and R², reflecting my implementation of an end-to-end regression pipeline and experimentation with housing data.

This project focuses on predicting housing prices using the Ames Housing dataset, a rich dataset containing 2,930 observations and 82 features that describe residential homes in Ames, Iowa. The goal is to build a machine learning model capable of accurately estimating house prices based on various structural and neighborhood-related factors.

The workflow follows a complete end-to-end machine learning pipeline, starting from data exploration to model evaluation. Exploratory Data Analysis (EDA) is performed to understand feature distributions, identify missing values, and uncover relationships between variables and the target variable (SalePrice). Visualization libraries such as Matplotlib and Seaborn are used to reveal patterns and insights.

## Key Steps

- Performed data cleaning and handled missing values  
- Encoded categorical variables using Label Encoding  
- Applied feature scaling with StandardScaler  
- Split dataset into training and testing sets  
- Built a baseline model using Linear Regression  
- Evaluated performance using MAE, MSE, and R² score  

The Linear Regression model serves as a starting point to understand how different features impact housing prices. Model performance is analyzed using standard regression evaluation metrics, providing insight into prediction accuracy and reliability.

## It also provides a strong base for further improvements, including:

- Implementing advanced models like Random Forest or XGBoost
- Performing hyperparameter tuning
- Enhancing feature selection and engineering techniques
