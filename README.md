## Employee Churn Prediction with Classification Models

Predictive modeling project exploring employee turnover using machine learning classification models in Python.

[Link to the respective website post](https://michael0k.github.io/python/demo/visualization/Employee-Churn-Prediction-with-Classification-Models/)


### Overview
- Goal: Build and evaluate machine learning models to predict which employees are likely to leave an organization.
- Stack: Python (pandas, scikit-learn), Google Colab/Jupyter Notebook, Looker Studio, Google BigQuery.

### Dataset
- Source: HR/employee churn dataset (e.g., IBM HR Analytics or similar).
- Included: Processed dataset and derived features used in modeling.

### Methods
- Cleaning: Imputation, encoding categorical variables, feature scaling.
- Modeling: Logistic Regression, Random Forests, Support Vector Machines, and other classifiers.
- Evaluation: Metrics such as accuracy, precision, recall, and confusion matrices to assess performance.

### Results
- Comparative performance of multiple classification models.
- Identification of key features influencing employee churn.
- Visualizations illustrating employee turnover and causes.

### How to Run
1) Load the dataset (CSV) into the workspace.
2) Execute the data preprocessing steps in the notebook.
3) Fit classification models and evaluate results interactively.

### Structure
- `data/`: dataset used for modeling
- `notebooks/`: analysis and model training
- `visualization/`: plots and evaluation charts

### Next
- Incorporate hyperparameter tuning (GridSearchCV/RandomizedSearchCV).
- Deploy as a simple Flask or Streamlit app for interactive usage.

### License
GNU GPL v3
