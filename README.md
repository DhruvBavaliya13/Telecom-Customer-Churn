# Telecom Customer Churn Prediction using ML

This project aims to predict customer churn in a telecom company using machine learning techniques. The objective is to help the company identify customers who are likely to stop using their services, enabling proactive retention strategies.

## 📊 Problem Statement

Customer churn is a major issue in the telecom industry. By analyzing customer data, we can build predictive models to forecast churn and assist businesses in improving customer retention and reducing losses.

## 📁 Dataset

* **Telco Customer Churn Dataset**: Contains customer demographic details, account information, service usage, and churn status.
* **Source**: [Kaggle Telecom Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) (or specify your source)

### Key Features:

* `gender`, `SeniorCitizen`, `Partner`, `Dependents`
* `tenure`, `MonthlyCharges`, `TotalCharges`
* Service features: `PhoneService`, `InternetService`, `StreamingTV`, etc.
* Target: `Churn` (Yes/No)

## 🛠️ Project Workflow

1. **Data Preprocessing**

   * Handling missing values and data cleaning.
   * Encoding categorical variables.
   * Feature scaling and selection.

2. **Exploratory Data Analysis (EDA)**

   * Visualizing churn distribution.
   * Analyzing relationships between features.
   * Identifying key churn indicators.

3. **Model Building**

   * Train-test split.
   * Machine learning models used:

     * Logistic Regression
     * Decision Tree
     * Random Forest
   * Hyperparameter tuning using GridSearchCV.

4. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-Score.
   * Model comparison to choose the best performer.

## 📝 Results

* The model with the best performance was **\Logistic Regression** achieving:

  * **Accuracy**: 1.00
  * **Precision**: 1.00
  * **Recall**: 1.00
  * **F1-Score**: 1.00

## 🛡️ Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
* Jupyter Notebook
* Machine Learning Algorithms (Supervised Learning)

## 🚀 How to Run

1. Clone this repository.
2. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Task.ipynb
   ```

## 📈 Future Improvements

* Implement real-time churn prediction API.
* Add SHAP & LIME explainability for model interpretation.

## 🤝 Acknowledgements

* Dataset Source: Kaggle
* Inspired by churn prediction case studies.

