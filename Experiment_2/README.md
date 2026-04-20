#  Experiment 2: House Price Prediction using Machine Learning

##  Objective
To build a machine learning model to predict house prices based on various features in the dataset.

##  Dataset
- File Name: House_Prediction_Dataset
- Description: The dataset contains information about houses such as area, number of bedrooms, bathrooms, and other features used to predict the price of a house.

##  Steps Performed

### 1. Data Loading
Loaded the dataset using pandas library.

### 2. Data Understanding
- Used `.info()` to check data types and missing values  
- Used `.describe()` to understand statistical summary  

### 3. Data Preprocessing
- Handled missing values (if any)  
- Removed duplicate rows  
- Converted categorical columns into numerical format using encoding  

### 4. Feature Selection
- Separated independent variables (X)  
- Selected target variable (y) → House Price  

### 5. Feature Scaling
- Applied StandardScaler to normalize the dataset  

### 6. Model Building
- Implemented **Linear Regression** algorithm  

### 7. Model Training
- Split dataset into training and testing sets  
- Trained model using training data  

### 8. Model Evaluation
- Evaluated performance using:
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score  

##  Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

##  Result
The model successfully predicts house prices based on input features. Evaluation metrics indicate the accuracy and performance of the model.

##  Future Scope
- Improve accuracy using advanced algorithms  
- Apply feature engineering  
- Perform hyperparameter tuning  

---
