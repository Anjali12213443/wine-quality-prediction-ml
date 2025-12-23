# Wine Quality Prediction Using Machine Learning

## Project Overview
This project focuses on predicting wine quality based on its chemical properties using machine learning techniques. The objective is to analyze key factors affecting wine quality and build accurate predictive models while generating actionable business insights for wineries.

---

## Dataset
- **Source:** Wine Quality Dataset
- **Size:** 1,999 samples, 12 features
- **Target Variable:** Wine quality (rating scale 0–10)
- **Key Features:** Alcohol, sulphates, volatile acidity, density, residual sugar

---

## Exploratory Data Analysis (EDA)
- Identified strong positive correlation between **alcohol content** and wine quality
- Observed class imbalance with most wines rated as medium quality
- Detected outliers in **residual sugar** and **volatile acidity**
- Visualized distributions, correlations, and feature relationships

---

## Data Preprocessing
- Handled outliers using the **Interquartile Range (IQR)** method
- Applied **StandardScaler** for feature normalization
- Verified no missing values in the dataset

---

## Feature Engineering
- Created new features:
  - `sugar_acidity_ratio`
  - `sulfur_dioxide_ratio`
- Selected important features using:
  - Recursive Feature Elimination (RFE)
  - Correlation analysis
- Reduced dimensionality using **PCA** while retaining 95% variance

---

## Model Building
### Classification
- **Model:** Random Forest Classifier
- **Accuracy:** ~90%
- Strong precision, recall, and F1-score for medium-quality wines

### Regression
- **Model:** Linear Regression
- **R² Score:** ~75%
- **RMSE:** ~0.65

### Clustering
- **K-Means:** 3 clusters, Silhouette Score ~0.57
- **DBSCAN:** Limited effectiveness due to data sparsity

---

## Key Insights
- Alcohol and sulphates are the strongest predictors of wine quality
- Higher-quality wines tend to have balanced acidity and higher alcohol content
- Clustering revealed distinct wine groups useful for marketing strategies

---

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Files in This Repository
- Jupyter Notebook with full analysis and modeling
- Final project report (PDF)

---

## Future Improvements
- Address class imbalance using resampling techniques
- Explore ensemble and boosting models
- Improve clustering with advanced distance metrics

---

## Author
**Anjali Velu Ramalingam**  
Graduate Student – Data Science / Analytics
