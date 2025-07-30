# Advertising Sales Prediction

This project demonstrates a complete machine learning workflow for predicting product sales based on advertising budgets across three media channels: TV, Radio, and Newspaper. Using exploratory data analysis, outlier handling, regression modeling, and performance evaluation, we aim to identify which advertising channel contributes most to sales.

## 📁 Dataset

The dataset consists of advertising budget and sales data with the following features:

- `TV Ad Budget ($)`
- `Radio Ad Budget ($)`
- `Newspaper Ad Budget ($)`
- `Sales ($)`

Data Source: *Standard Advertising Dataset (CSV format)*

---

## 📌 Objectives

- Understand the relationship between advertising budgets and sales.
- Visualize data distribution and correlation.
- Handle outliers effectively to improve model performance.
- Build and evaluate multiple Linear Regression models:
  - With original data (with outliers)
  - After outlier removal
  - With feature scaling

---

## 🔧 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

---

## 📊 Steps Performed

### 1. Data Loading & Exploration
- Imported and displayed dataset information, shape, and statistical summary.
- Renamed columns for clarity.
- Visualized relationships using pairplots and boxplots.

### 2. Outlier Detection and Removal
- Identified outliers using IQR method, particularly in `Newspaper Ad Budget`.
- Created a cleaned dataset after removing outliers.

### 3. Exploratory Data Analysis (EDA)
- Plotted distributions of all features and target.
- Generated a heatmap for correlation analysis.

### 4. Regression Modeling
- Built Linear Regression models:
  - On original data with outliers
  - On cleaned data (without outliers)
  - On scaled data
- Evaluated using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)

### 5. Comparison Table
- Compiled a summary table comparing model performance across all versions.

---

## 📈 Results & Conclusion

- **TV and Radio ads** showed strong correlation with Sales, while Newspaper ads had the least impact.
- Removing outliers improved model accuracy and reduced error metrics.
- Scaling had minor effect but helped normalize features for better training stability.

---

## 📚 Learnings

- Data preprocessing is crucial for accurate predictions.
- Linear regression is effective when relationships are linear and features are well-distributed.
- Outlier removal significantly enhances model performance and reliability.

---

## 📂 Repository Structure

