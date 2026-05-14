# Loan Approval Prediction Using Decision Tree

## Project Overview
This project uses Machine Learning to predict whether a loan application will be approved or rejected using a Decision Tree Classifier.

The project demonstrates the complete machine learning workflow including:
- Data cleaning
- Missing value handling
- Exploratory Data Analysis (EDA)
- Feature engineering
- Categorical encoding
- Model training
- Model evaluation
- Feature importance analysis

---

## Dataset Information

The dataset contains applicant demographic and financial information together with the target variable `Loan_Status`.

### Features Used
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

### Target Variable
- Loan_Status
  - Y = Approved
  - N = Rejected

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Checked data types
- Prepared features for modeling

### 2. Exploratory Data Analysis (EDA)
- Dataset structure analysis
- Distribution analysis
- Missing value analysis
- Correlation analysis

### 3. Model Building
A Decision Tree Classifier was used to train the prediction model.

### 4. Model Evaluation
The model was evaluated using:
- Accuracy score
- Confusion matrix
- Classification metrics

---

## Model Performance

The Decision Tree model achieved an accuracy of approximately:

```python
Accuracy: 84.55%
