# Titanic Prediction using Logistic Regression

This project aims to predict the survival of passengers on the Titanic using Logistic Regression.
The data is sourced from Kaggle and includes various features about passengers such as age, gender, class, and more.
## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset and handled missing values.
- Converted categorical variables into numerical values for analysis.
- Standardized and normalized the data as needed.

### 2. Exploratory Data Analysis
- Visualized the relationships between features and survival rate using plots.
- Analyzed the impact of variables like age, sex, and passenger class on survival.

### 3. Train-Test Split
- Split the data into training and testing sets for model validation.
- Ensured the target variable (`Survived`) was balanced between splits.

### 4. Logistic Regression
- Built a Logistic Regression model using the training set.
- Tuned hyperparameters to optimize performance.

### 5. Model Evaluation
- Evaluated the model's performance using metrics such as:
  - Accuracy
