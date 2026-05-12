# AIML Project-Based Learning (PBL)

# Predictive Analytics for Urban Water Demand

## Overview
This project is developed for PCS-253 AIML Project-Based Learning (PBL).

The main objective of this project is to predict and classify urban water consumption using Machine Learning techniques. Multiple models are implemented and compared to improve prediction accuracy and classification performance.

The project is divided into three phases showing progressive improvement in dataset preparation, preprocessing, model training, and evaluation.

---

# Project Structure

## Phase 1 - Initial Development

### Objective
To build a basic machine learning project using the raw dataset.

### Work Done
- Created initial dataset
- Basic project implementation
- Problem understanding
- Initial data analysis

### Files
- dataset.csv
- report.pdf

---

## Phase 2 - Model Improvement

### Objective
To improve dataset quality and evaluate machine learning models.

### Work Done
- Data cleaning
- Feature analysis
- Data preprocessing
- Model evaluation using:
  - MSE
  - RMSE
  - R² Score

### Files
- Phase2.ipynb
- improved_dataset.csv
- report.pdf

---

## Phase 3 - Final Implementation

### Objective
To build an optimized machine learning system for predicting urban water demand.

### Features Used
- Household_Size
- Income_Level
- Garden_Area
- Rainfall_mm
- Temperature_C
- Seasonal_Index
- Water_Price
- Appliance_Count
- Leakage_Factor

### Additional Engineered Features
- Per_Person_Usage
- Garden_Impact
- Water_Intensity

### Machine Learning Models Used
- Linear Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree

### Work Done
- Final dataset preparation
- Data preprocessing
- Feature scaling using StandardScaler
- Train-test split
- Model training and prediction
- Model comparison
- Performance evaluation
- Data visualization and graphs

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- ROC-AUC Curve

### Visualizations
- Correlation Heatmap
- Histogram
- Boxplot
- Scatter Plot
- Confusion Matrix
- ROC Curve
- Feature Importance Graph

### Best Performing Model
Decision Tree achieved the best performance based on F1 Score.

### Files
- Phase3.ipynb
- final_dataset.csv
- report.pdf

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

# Workflow

Dataset → Data Cleaning → Feature Engineering → Feature Scaling → Model Training → Prediction → Evaluation → Visualization

---

# Conclusion
This project successfully predicts and classifies urban water usage using multiple machine learning models. Different preprocessing and evaluation techniques were applied to improve model performance and compare different algorithms effectively.

---

# Future Scope
- Use advanced models like Random Forest and XGBoost
- Real-time water demand prediction
- Deploy using Flask or Streamlit
- Add live dashboard and monitoring system

---

# GitHub Repository

[Python_PBL Repository](https://github.com/nitinsingh34678-ctrl/Python_PBL?utm_source=chatgpt.com)
