#  Customer Churn Prediction using Machine Learning

##  Project Overview

Customer churn prediction is one of the most important business applications of Machine Learning. This project predicts whether a customer is likely to leave (churn) or continue using the company's services based on customer demographic information, account details, and service usage.

The model helps businesses identify customers who are at high risk of leaving so that retention strategies can be implemented proactively.

---

##  Problem Statement

Customer acquisition is significantly more expensive than customer retention. Therefore, predicting customer churn allows businesses to:

* Improve customer retention
* Reduce revenue loss
* Increase customer satisfaction
* Make data-driven business decisions

This project builds a machine learning classification model to predict customer churn using customer data.

---

##  Dataset

* **Dataset:** Telco Customer Churn Dataset
* **Total Records:** 7,043 Customers
* **Features:** 21
* **Target Variable:** `Churn`

Example Features:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges

Target:

* **Yes** → Customer will churn
* **No** → Customer will stay

---

##  Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Workflow

### 1. Data Collection

* Load the dataset
* Understand data structure

### 2. Data Preprocessing

* Handle missing values
* Remove duplicates
* Convert categorical variables
* Feature Encoding
* Feature Scaling (if required)

### 3. Exploratory Data Analysis (EDA)

* Customer distribution
* Churn analysis
* Correlation analysis
* Feature visualization

### 4. Model Building

Machine Learning algorithms used:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

### 5. Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

### 6. Prediction

The final trained model predicts whether a customer is likely to churn based on the given customer information.

---

##  Results

The trained model achieved high prediction performance after preprocessing and feature engineering.

Performance metrics include:

* High Accuracy
* Good Precision and Recall
* Effective identification of customers likely to churn

*(Update this section with your actual model accuracy after training.)*

Example:

```
Model Accuracy : 84.6%
Precision      : 82%
Recall         : 79%
F1 Score       : 80%
```

---

##  Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── requirements.txt (optional)
```

---

##  How to Run

### Clone Repository

```bash
git clone https://github.com/YasaswiniPilla/Customer-Churn-Prediction.git
```

### Move into Project Folder

```bash
cd Customer-Churn-Prediction
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Open Notebook

Run the Jupyter Notebook or Google Colab notebook.

---

## 📷 Sample Visualizations

The project includes various visualizations such as:

* Churn Distribution
* Contract Type vs Churn
* Internet Service Analysis
* Monthly Charges Distribution
* Correlation Heatmap
* Confusion Matrix

---

##  Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* LightGBM Model
* SHAP Explainability
* Streamlit Web Application
* Flask Deployment
* Docker Containerization
* Cloud Deployment

---

## 🎓 Learning Outcomes

Through this project, I learned:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Classification
* Model Evaluation
* Business Problem Solving using ML

---

##  Author

**Yasaswini Pilla**

B.Tech – Information Technology

Machine Learning & Data Science Enthusiast

GitHub: https://github.com/YasaswiniPilla

---

##  If you found this project helpful, don't forget to Star this repository!
