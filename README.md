**Industrial Copper Modeling:**
This project focuses on building machine learning models to address challenges in the copper industry, specifically related to sales and pricing. The goal is to develop regression and classification models that can accurately predict selling prices and classify leads as successful or unsuccessful. The project also includes creating a Streamlit web application for easy input and prediction.

**Skills Developed:**
Throughout this project, you will gain proficiency in the following skills:
* Python scripting
* Data preprocessing techniques, including handling missing values, outlier detection, and data normalization
* Exploratory Data Analysis (EDA) using libraries such as Pandas, NumPy, Matplotlib, and Seaborn
* Regression modeling to predict continuous variables
* Classification modeling to predict binary variables
* Feature engineering to create new informative representations of the data
* Model evaluation using appropriate metrics and techniques, such as cross-validation and grid search
* Creating an interactive web application using the Streamlit library

**Problem Statement:**
The copper industry faces challenges in dealing with less complex but skewed and noisy sales and pricing data. Manual predictions are time-consuming and may not yield optimal pricing decisions. Additionally, capturing leads and evaluating their potential as customers can be difficult. The project aims to address these challenges by developing machine learning models for regression and classification tasks.

***Approach***
__Data Understanding:__
* Identify variable types (continuous, categorical) and their distributions.
* Treat rubbish values in 'Material_Reference' starting with '00000' as null.
* Treat reference columns as categorical variables.
  
**Data Preprocessing:**
* Handle missing values using mean/median/mode imputation.
* Treat outliers using IQR or Isolation Forest from the sklearn library.
* Identify skewness and apply appropriate data transformations, such as log or Box-Cox transformations.
* Encode categorical variables using suitable techniques, such as one-hot encoding or label encoding.

**Exploratory Data Analysis (EDA):**
* Visualize outliers and skewness using Seaborn's boxplot, distplot, and violinplot.
* Identify highly correlated columns using a heatmap and drop them.
  
**Feature Engineering:**
Engineer new features, if applicable, to create more informative representations of the data.

**Model Building and Evaluation:**
* Split the dataset into training and testing/validation sets.
* Train and evaluate regression models (e.g., ExtraTreesRegressor, XGBRegressor) using appropriate evaluation metrics.
* Optimize model hyperparameters using techniques such as cross-validation and grid search.
* Interpret the model results and assess performance based on the defined problem statement.
  
**Model GUI using Streamlit:**
* Create an interactive web application using the Streamlit module.
* Allow users to input values for each column except 'Selling_Price' or 'Status'.
* Apply the same preprocessing steps used during model training to the new data.
* Predict the selling price or status based on the chosen task (regression or classification).
* Display the predicted output to the user.

**Data:**
  The dataset provided contains the necessary information for regression and classification modeling.

**Instructions:**
* Install the required dependencies listed in the requirements.txt file.
* Run the preprocessing script to handle missing values, outliers, and transformations.
* Execute the model building script to train and optimize the regression and classification models.
* Launch the Streamlit application to interact with the trained models and make predictions on new data.
  
**Conclusion:**
This project equips you with practical skills in Python programming, data preprocessing, EDA, machine learning modeling, and web application development. By completing this project, you will gain valuable experience in solving real-world problems in the manufacturing domain using advanced techniques and industry best
