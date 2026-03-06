# Customer Churn Prediction

This project analyzes the Telco Customer Churn dataset to identify patterns that lead to customer churn and build machine learning models capable of predicting whether a customer is likely to leave a service.

The goal of the project is to demonstrate the full machine learning workflow including data inspection, preprocessing, visualization, model training, and evaluation.

## Dataset

The dataset contains information about telecom customers, including:

* Customer demographics
* Account information
* Services subscribed to
* Billing details
* Whether the customer churned

These features are used to train models that predict customer churn.

## Project Workflow

The notebook follows a structured machine learning workflow:

1. **Data Inspection**
   Explore the dataset and understand the available features.

2. **Data Preprocessing**
   Clean the dataset, handle missing values, and encode categorical variables.

3. **Data Visualization**
   Visualize patterns in the data to better understand factors related to churn.

4. **Feature Scaling and Training**
   Prepare the dataset for machine learning models.

5. **Model Training**

   * Logistic Regression
   * Random Forest Classifier

6. **Model Evaluation**
   Evaluate model performance using accuracy and confusion matrices.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook

## Results

The trained models are able to predict customer churn based on service usage and customer attributes. Model performance is evaluated using classification metrics and confusion matrices.

## How to Run the Project

Clone the repository:

```
git clone https://github.com/kp1028/customer-churn-prediction.git
```

Navigate into the project folder:

```
cd customer-churn-prediction
```

Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:

```
jupyter notebook telco_customer_churn.ipynb
```
