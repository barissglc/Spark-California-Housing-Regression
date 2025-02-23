# Spark-California-Housing-Regression

🚀 **Advanced Regression Modeling with PySpark**

This project utilizes PySpark to perform **advanced data preprocessing, feature engineering, and machine learning modeling** on the **California Housing dataset**. The goal is to predict housing values by applying state-of-the-art regression techniques, including **Linear Regression, Random Forest, and Gradient Boosting Trees**.

**(RMSE: 44570.355263381374)**

**(R2: 0.79707348968939)**

---

## 📌 Table of Contents
- [📖 About the Project](#-about-the-project)
- [📊 Dataset](#-dataset)
- [🛠️ Technologies Used](#-technologies-used)
- [📈 Model Training and Evaluation](#-model-training-and-evaluation)
- [📉 Visualizations](#-visualizations)

---

## 📖 About the Project

🔹 This project establishes a **comprehensive end-to-end workflow** for predicting house values using PySpark. The key components include:

✅ **Data Preprocessing**: Handling missing values, filtering outliers.
✅ **Feature Engineering**: Log transformations, scaling, and feature creation.
✅ **Model Training**: Implementation of **Linear Regression, Random Forest, and Gradient Boosting Trees**.
✅ **Hyperparameter Tuning**: Grid search with **5-fold cross-validation**.
✅ **Evaluation Metrics**: **RMSE, MAE, and R²** for performance assessment.

💡 The **best-performing model** identified in this study is **Random Forest**, based on **evaluation metrics and predictive accuracy**.

---

## 📊 Dataset

📌 The **California Housing dataset** consists of various features related to housing values in California, such as:

| Feature Name        | Description  |
|--------------------|-------------|
| `longitude`, `latitude` | Geographical coordinates |
| `housing_median_age` | Median age of the houses |
| `total_rooms`, `total_bedrooms` | Total number of rooms and bedrooms |
| `population`, `households` | Population and total households |
| `median_income` | Median income of households |
| `median_house_value` | **Target variable** - Median housing price |
| `ocean_proximity` | Categorical variable indicating proximity to the ocean |

---

## 🛠️ Technologies Used

🔹 **Python** 🐍  
🔹 **PySpark** ⚡  
🔹 **Matplotlib & Seaborn** 📊 *(for visualizations)*  
🔹 **Pandas** 📝 *(for data manipulation)*  

---

## 📈 Model Training and Evaluation

✔ **Pipeline**: The data preprocessing steps (handling missing values, log transformations, feature scaling) are integrated into a seamless machine learning pipeline.  
✔ **Hyperparameter Tuning**: Each model undergoes **grid search** and **5-fold cross-validation** to fine-tune the hyperparameters.  
✔ **Performance Metrics**: Models are evaluated using **RMSE, MAE, and R²** to ensure optimal performance.  
✔ **Final Outcome**: The **Random Forest model** achieved the highest accuracy and best overall performance. (RMSE: 44570.355263381374)

---

## 📉 Visualizations

📊 **Key insights are visualized using Matplotlib & Seaborn**:

✅ **Histograms**: Distribution of `median_house_value` and `log_median_income`.  
✅ **Scatter Plot**: Relationship between `housing_median_age` and `log_median_income`.  
✅ **Correlation Heatmap**: Displays feature correlations to identify strong predictors.  
✅ **Feature Importances**: Visualization of key features in tree-based models.  

---

🚀 **Developed by Barış Güleç**  
