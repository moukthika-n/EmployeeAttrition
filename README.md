# Employee Attrition Prediction

## Project Overview

This project predicts employee attrition using machine learning models. The dataset used is the [Employee Attrition Dataset](https://www.kaggle.com/datasets/patelprashant/employee-attrition) from Kaggle. The models implemented include Logistic Regression, Decision Tree, and Random Forest to evaluate the likelihood of employees leaving the company.

## Dataset

The dataset used for this project can be found on Kaggle: [Employee Attrition Dataset](https://www.kaggle.com/datasets/patelprashant/employee-attrition). It contains data on employee demographics, performance, and job roles, which are used to predict whether an employee will leave or stay.

## Phases of the Project

### 1. Data Preprocessing
- Cleaned the dataset by handling missing values and outliers.
- Performed feature engineering and normalization of relevant features.
- Categorical data was encoded for model compatibility.

### 2. Model Building
- **Logistic Regression**: Built a binary classification model to predict employee attrition.
- **Decision Tree**: Implemented a decision tree model to capture non-linear relationships between features.
- **Random Forest**: Built an ensemble model using random forests for robust predictions.

### 3. Performance Metrics
Evaluated each model based on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

### 4. Insights and Conclusions
- Discussed key insights derived from the models.
- Compared the performance of each algorithm in predicting employee attrition.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/EmployeeAttrition.git
   cd EmployeeAttrition
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   -Launch Jupyter Notebook and open employee_attrition.ipynb to view the analysis.

## Technology Stack

- **Programming Language**: Python
- **Data Preprocessing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
- **Visualization**: Matplotlib, Seaborn
- **Jupyter Notebook**: For running the analysis and model-building process
