## Customer Churn Prediction Model

In this ML model, the goal is to predict which customers are likely to churn based on their behavior and interaction with the platform on the shopping dataset. 

### Features
- **Data Preprocessing:** Includes handling missing values, encoding categorical variables, and feature scaling.
- **Model Building:** Utilizes Logistic Regression and Random Forest classifiers to predict churn.
- **Model Evaluation:** Assesses model performance using accuracy, ROC-AUC, precision, recall, and F1 score.
- **Model Tuning:** Uses GridSearchCV to optimize model parameters for improved performance.
- **Model Interpretation:** Analyzes feature importance, partial dependence display and SHAP values to understand driving factors behind predictions.

### Data
The dataset titled "Online Shopping Dataset" includes customer demographics, transaction details, and churn indicators. Key features include customer tenure, purchase frequency, and changes in spending behavior.

It is sourced from Kaggle at https://www.kaggle.com/jacksondivakarr/online-shopping-dataset

License: Apache 2.0

### Files Included
- **`customer_churn_prediction.ipynb`**: Jupyter Notebook containing the full analysis and model development.
- **`OnlineShopping_Dataset.csv`**: Dataset used for training and testing the model.
- **`requirements.txt`**: List of libraries required to run the project.


### How to Run
1. **Clone this repository**:  
git clone https://github.com/periGH/customer-churn-prediction.git

2. **Install required libraries**:  
pip install -r requirements.txt

3. **Run the Jupyter Notebook**:  
jupyter notebook customer_churn_prediction.ipynb