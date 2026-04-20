# Experiment 3: Titanic Survival Prediction

##  Objective
To build a classification model that predicts whether a passenger survived or not using the Titanic dataset.

---

## Dataset
- File Name: titanic.csv
- Description: The dataset contains passenger details such as age, gender, ticket class, fare, and embarkation port.
- Target Variable: Survived (0 = Not Survived, 1 = Survived)

---

## Steps Performed

### 1. Data Loading
- Loaded dataset using pandas

### 2. Data Cleaning
- Dropped unnecessary columns:
  - PassengerId
  - Name
  - Ticket
  - Cabin

### 3. Handling Missing Values
- Filled missing values:
  - Age → median
  - Fare → median
  - Embarked → mode
- Removed any remaining null values

### 4. Encoding Categorical Data
- Converted:
  - Sex → male = 0, female = 1
- Applied One-Hot Encoding on:
  - Embarked column

### 5. Feature Selection
- Input Features (X): All columns except 'Survived'
- Target Variable (y): Survived

### 6. Train-Test Split
- Split dataset into:
  - 80% Training data
  - 20% Testing data

### 7. Feature Scaling
- Applied StandardScaler on:
  - Age
  - Fare

### 8. Model Building
- Used Logistic Regression algorithm

### 9. Model Training
- Trained model using training dataset

### 10. Model Evaluation
Evaluated model using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Result
The Logistic Regression model successfully predicts passenger survival. The evaluation metrics indicate the model’s performance in classification tasks.

---

## Future Scope
- Apply advanced models (Random Forest, Decision Tree)
- Perform feature engineering
- Improve accuracy using hyperparameter tuning

---
