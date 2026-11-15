# Commercial Flight Delay Prediction ✈️

## Project Overview
This repository contains an end-to-end Machine Learning pipeline designed to predict commercial flight delays. The project aims to classify whether a flight will be delayed (by more than 15 minutes) based on various flight characteristics, departure times, and carrier data.

## Dataset
The models were trained on a subset of the **2023 US Commercial Flights Dataset** (500,000 records). 
*Note: The raw `.csv` data file is not included in this repository due to GitHub's file size limits.*

## Machine Learning Pipeline
1. **Exploratory Data Analysis (EDA):** Visualizing delay distributions by time of day, day of the week, and airlines.
2. **Data Preprocessing:** Handling missing values, preventing data leakage (dropping post-departure features), and applying `OrdinalEncoder` and `StandardScaler`.
3. **Modeling:** Training and evaluating multiple classification algorithms:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
4. **Evaluation:** Models are evaluated using Accuracy, Precision, Recall, F1-Score, Confusion Matrices, and ROC-AUC curves. 

## Key Technologies Used
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Google Colab

## Results Insight
The project utilizes Feature Importance extraction (via Decision Tree and Random Forest) to identify the top factors contributing to flight delays, offering actionable insights into aviation data.
