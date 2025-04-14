# Breast Cancer Prediction Using Machine Learning

This project focuses on building a reliable model to predict whether a breast tumor is benign or malignant, using clinical features from the Breast Cancer Wisconsin (Diagnostic) Dataset. The prediction is performed using a Support Vector Classifier (SVC), a powerful model particularly effective for binary classification tasks like this one.

## Dataset

- **Source**: Breast Cancer Wisconsin (Diagnostic) Dataset
- **Features**: 30 numerical features derived from digitized images of fine needle aspirates (FNA) of breast masses
- **Target**: Diagnosis — 0 (Benign), 1 (Malignant)

## Workflow

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)
- Feature Selection
- Train-Test Split
- Model Training using Support Vector Classifier (SVC)
- Performance Evaluation

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Heatmaps and Visualizations for Feature Correlation

## Future Enhancements

- Try additional models like Random Forest, KNN, or Logistic Regression for comparison
- Integrate deep learning approaches (ANN/CNN)
- Deploy the model as a web-based diagnostic tool using Streamlit or Flask