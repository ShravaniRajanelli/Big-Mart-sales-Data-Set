# Big Mart Sales Prediction
This project involves the analysis and prediction of sales using the Big Mart Sales dataset. The dataset contains information about various products and their sales across different outlets. The main objective is to build a predictive model that can estimate the sales of a product based on various features.

## Dataset Overview
The Big Mart Sales dataset consists of the following columns:

* Item_Identifier: Unique identifier for each product.
* Item_Weight: Weight of the product.
* Item_Fat_Content: Categorical variable indicating the fat content of the product (e.g., Low Fat, Regular).
* Item_Visibility: Percentage of total display area of all products in a store allocated to the particular product.
* Item_Type: Categorical variable indicating the category of the product.
* Item_MRP: Maximum Retail Price (MRP) of the product.
* Outlet_Identifier: Unique identifier for each outlet/store.
* Outlet_Establishment_Year: Year of establishment for the outlet.
* Outlet_Size: Categorical variable indicating the size of the outlet.
* Outlet_Location_Type: Categorical variable indicating the type of location of the outlet.
* Outlet_Type: Categorical variable indicating whether the outlet is a grocery store or a supermarket.
  
## Problem Statement
The goal of this project is to predict the sales of products in the Big Mart stores. It is a regression problem, and we will use machine learning models to predict the sales based on the provided features.

## Analysis Steps
### Data Exploration:
* Explored the distribution of features.
* Handled missing values and outliers.
* Created visualizations to gain insights into the data.
### Feature Engineering:
* Derived new features from existing ones.
* Handled categorical variables and encoded them appropriately.
### Data Preprocessing:
* Imputed missing values.
* Encoded categorical variables.
* Scaled numerical features.
### Model Selection:
* Explored various regression models (e.g., Linear Regression, Random Forest, XGBoost).
* Evaluated models using cross-validation.
### Model Training:
* Selected the best-performing model.
* Trained the model on the training dataset.
### Model Evaluation:
* Evaluated the model on the testing dataset.
* Assessed performance using metrics such as Mean Squared Error (MSE) and R-squared.
## Results
The final model achieved a Mean Squared Error of X on the testing dataset. Detailed results and insights can be found in the Jupyter notebook here.

Dependencies
Python 
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter.

Feel free to explore and contribute to this project! If you have any questions or suggestions, please contact me at shravanirajanelli@gmail.com.

Happy coding! 🛒📊
