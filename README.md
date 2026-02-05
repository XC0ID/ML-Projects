# Machine Learning Projects Repository 🚀

This repository contains multiple machine learning and data science projects, each organized into separate folders. Every project focuses on a real-world problem and demonstrates end-to-end ML workflows including data preprocessing, modeling, evaluation, and insights.


## 📖 Table of Contents

- [The Vicious Cycle of Social Media Addiction](#the-vicious-cycle-of-social-media-addiction)
- [Wine Quality Prediction A Machine Learning Journey](#wine-quality-prediction-a-machine-learning-journey)
- [Spare Part Demand Forecasting](#spare-part-demand-forecasting)
- [ Bank Customer Churn Prediction](#bank-customer-churn-prediction)
- [Nursery Admission Prediction](#nursery-admission-prediction)
  
---
* ## The Vicious Cycle of Social Media Addiction


This project focuses on building and evaluating a machine learning model using Python.  
The workflow includes data preprocessing, feature engineering, model training, and performance evaluation.
From infinite scrolls to data-driven goals. Unraveling the patterns of digital dependency among students.

---
### 🧐 The Mission
Social media is designed to keep us hooked, but what actually drives the addiction? Is it the hours spent? The sleep lost? Or the mental health toll?

This project isn't just about code; it's an investigation. We are diving deep into student data to analyze the "Vicious Cycle of Social Media Addiction"—understanding the triggers, visualizing the conflicts, and building machine learning models to predict the addiction score.

---
### 🚀 Features
- Data cleaning and preprocessing  
- Feature selection and transformation  
- Model training using Scikit-learn  
- Model evaluation using performance metrics  

---

📂 The Evidence (Dataset)
We are working with the Students Social Media Addiction.csv file. The key suspects (features) in our investigation include:

⏳ **Avg Daily Usage Hours**: The time sunk into the screen.

🛌 **Sleep Hours Per Night**: The rest sacrificed for the scroll.

🧠 **Mental Health Score**: The psychological impact.

⚔️ **Conflicts Over Social Media**: The real-world friction.

📊 **Addicted Score**: The target variable we are trying to predict.


🛠️ The Detective's Toolkit (Tech Stack)
We are armed with the heavy hitters of the Python data science ecosystem:

---
#### ⚙️ The Pipeline (Methodology)
1. 🧹 **Data Cleaning & Preprocessing**
Raw data is messy. We convert object types to numerics and handle errors to ensure our models get a clean diet of data.

2. 🔍 **Exploratory Data Analysis (EDA)**
We don't guess; we look.

Correlation Heatmaps: Visualizing how Sleep battles Usage and how Mental Health ties into Addiction.

3. ⚔️**The Model Battle Royale**
We aren't just trying one algorithm; we are throwing them all into the arena to see which one predicts addiction best. Our Pipeline includes:

The Linear Legion: LinearRegression, Ridge, Lasso, ElasticNet, BayesianRidge.
The Tree Titans: DecisionTree, RandomForest, ExtraTrees, GradientBoosting.
The Support Vector Scout: SVR.
The Neighbor: KNeighborsRegressor.
The Brain: MLPRegressor (Neural Network).

---
### 📈 Results

Model performance is evaluated using appropriate metrics such as:

* R² Score
  
* Mean Squared Error (MSE)
  
* Accuracy (if classification)
  
---
* ## Wine Quality Prediction A Machine Learning Journey

This project uses **Machine Learning** to analyze wine characteristics and predict its quality — blending data science with a splash of creativity.
> 
* Alcohol: The body of the data.
* Proline & Flavanoids: The complex undertones.
* Class: The origin label we are trying to predict (Cultivator 1, 2, or 3).
---
### 🌟 Project Snapshot
This notebook explores a wine dataset and builds predictive models to understand how chemical properties influence wine quality.

---
### 🧠 What’s Inside the Bottle?
✔ Data Cleaning & Exploration  
✔ Feature Engineering  
✔ Machine Learning Model Training  
✔ Model Evaluation & Performance Metrics  
✔ Visual Insights & Interpretations  

---
### 📂 Project Structure
📁 Wine-Quality-Prediction

├── 🍷 Wine.ipynb 

├── 📘 Wine dataset.csv

└── 📦 README.md 

---
### 🛠️ Tools & Ingredients Used
| Category | Tools |
|-------|------|
| Language | Python 🐍 |
| Libraries | NumPy, Pandas |
| ML | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---
### 🧪 The Blind Taste Test (Modeling)
* 🧐 The Traditionalist: Logistic Regression
* 📏 The Precisionist: SVM (Support Vector Machine)
* 🏘️ The Local: KNN (K-Nearest Neighbors)
* 🌳 The Organic Grower: Decision Tree
* 🌲 The Estate Blend: Random Forest
* 🚀 The Modernist: Gradient Boosting
---
### 📊 Model Performance

The model is evaluated using:

* ✅ R² Score
* ✅ Mean Squared Error (MSE)
* ✅ Prediction Accuracy (if classification)

Performance tuning can further enhance prediction quality.

---
* ## Spare Part Demand Forecasting

A machine learning–based project to forecast spare part demand using historical inventory data. This project helps optimize inventory management by predicting future demand trends, reducing stockouts and overstock situations.

---
### 🚀 Project Overview

Accurate demand forecasting is critical for efficient inventory control. This project uses historical spare part inventory data and applies data preprocessing, exploratory data analysis (EDA), and machine learning models to predict future demand.

The core implementation is done in a Jupyter Notebook for clarity and experimentation.

---
### 📂 Project Structure

```
├── Forecasting.ipynb          # Main notebook for data analysis & modeling

├── spare_part_inventory.csv  # Dataset used for forecasting

├── README.md                 # Project documentation
```

---
### 🧠 Workflow

1. **Data Loading** – Import and inspect the dataset
2. **Data Preprocessing** – Handle missing values, formatting, and feature engineering
3. **Exploratory Data Analysis (EDA)** – Understand patterns and trends
4. **Model Building** – Train machine learning models for forecasting
5. **Evaluation** – Measure performance using appropriate metrics
6. **Prediction** – Generate demand forecasts

---
### 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models
* **Jupyter Notebook** – Interactive development

---
### 📊 Dataset

* **File:** `spare_part_inventory.csv`
* Contains historical records of spare parts and their demand
* Used for training and testing forecasting models
---
### 🔮  Technical Implementation

#### ⭐ Feature Engineering
The model generates several time-based and statistical features to capture demand patterns:

* **Rolling Usage**: avg_usage_7d and avg_usage_30d to track short and long-term trends.
* **Temporal Features**: Extraction of day_of_week, month, and is_weekend to capture seasonal or weekly cycles.
* **Inventory Metrics**: days_of_inventory (current stock relative to usage rate) and lead_time_demand.

#### ⭐ Inventory Logic
The simulation uses the following parameters to flag risks:

* **Initial Stock**: 110 units (assumed).
* **Supplier Lead Time**: 7 days.
* **Stockout Target**: A binary flag (stockout_next_7d) is triggered if current stock is insufficient to cover the average demand during the 7-day lead time. 
---
### 📈 **Results**

* The model learns historical demand patterns
* Provides predictions that can support inventory planning decisions

---
* ## Bank Customer Churn Prediction
This project focuses on predicting **customer churn** using machine learning techniques. The goal is to identify customers who are likely to leave the bank, helping businesses take proactive retention actions.

---
### 📂 Project Structure

```
├── Bank_churn_model_evaluation.ipynb

├── BankChurners.csv
  
├── README.md                          
```

---
### 📊 Dataset Overview
* **Source:** Bank customer data
* **Target Variable:** `Attrition_Flag` (Churn / Existing Customer)
* **Rows:** ~10,000 customers
* **Features:** Demographics, account information, transaction behavior

##### Key Feature Categories
* Customer demographics (Age, Gender, Education)
* Account details (Credit limit, Card category)
* Transaction behavior (Transaction count, amount)
---
### ⚙️ Machine Learning Models Used
The notebook evaluates multiple models to find the best-performing one:
* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* Support Vector Machine (SVM)
* (Optional extensions: XGBoost, LightGBM, CatBoost)

Pipelines are used where appropriate for:
* Feature scaling
* Clean preprocessing

---
### 📈 Model Evaluation Metrics
Models are evaluated using:
* Accuracy
* ROC-AUC Score
* Confusion Matrix
* Classification Report

Visualization includes:
* ROC Curves
* Performance comparison plots

---
### 🧠 Key Insights
* Tree-based models generally outperform linear models
* Transaction behavior features are strong churn indicators
* Ensemble models provide better generalization

---
### 🔮 Future Improvements
* Hyperparameter tuning (GridSearchCV / Optuna)
* Advanced ensemble stacking
* Feature importance & SHAP explainability
* Deployment using Flask / FastAPI

---
* ## Nursery Admission Prediction 

This project applies Machine Learning algorithms to predict nursery school admission outcomes based on various socio-economic and family-related features. The dataset used is the well-known Nursery dataset from the UCI Machine Learning Repository.

---
### 📂 Project Structure
#### 📦 Nursery
 ┣ 📜 Nursery.ipynb        # Jupyter Notebook with data analysis & ML models
 
 ┣ 📜 nursery.csv          # Dataset file
 
 ┣ 📜 README.md            # Project documentation
 
 ---
### 📊 Dataset Description
The Nursery dataset is derived from a hierarchical decision model originally developed to rank nursery school applications.

#### 🔑 Features
parents – Parents' occupation
has_nurs – Child's nursery status
form – Family form
children – Number of children
housing – Housing condition
finance – Financial status
social – Social condition
health – Health condition

#### 🎯 Target Variable
class – Admission decision,not_recom,recommend,very_recom,priority,spec_prior

#### ⚙️ Technologies Used
Python,Pandas,NumPy,Scikit-learn,Matplotlib / Seaborn,Jupyter Notebook

---
### 🧠 Machine Learning Models Used
**The notebook explores and compares multiple ML algorithms, such as: /** 
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
(Models can be extended or ensembled for better performance.)

---
### 📈 Workflow
* Data Loading (nursery.csv)
* Data Preprocessing & Encoding
* Exploratory Data Analysis (EDA)
* Model Training
* Model Evaluation (Accuracy, ROC-AUC, etc.)
* Performance Comparison
---
### ✅ Results
* Achieved strong classification accuracy
* Compared multiple algorithms to find the best-performing model
* Demonstrated effective preprocessing for categorical data
---
