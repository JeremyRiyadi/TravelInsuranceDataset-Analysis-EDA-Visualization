# Heart Disease Dataset Analysis - EDA & Visualization

This project is an exploratory data analysis (EDA) of the Heart Disease dataset. The analysis focuses on understanding the distribution of key health indicators and identifying patterns or correlations that may contribute to the presence of heart disease.

The project includes data cleaning, descriptive statistics, various visualizations (bar charts, boxplots, histograms, heatmaps), and insights drawn from the data to help inform further machine learning modeling or clinical interpretations.

---

## 📊 Main Objectives

- Explore the distribution of key health-related features
- Visualize relationships between independent features and heart disease status
- Identify possible outliers and data imbalance
- Analyze feature correlation with heart disease
- Understand which variables might contribute most to predicting heart disease

---

## 🛠 Tools & Libraries Used

- Python
- Pandas (data handling & manipulation)
- Matplotlib & Seaborn (data visualization)
- NumPy (numerical operations)
- Plotly (interactive plots)
- Jupyter Notebook (interactive analysis)

---

## 🧠 Key Analyses & Visualizations

- **Boxplots & Histograms**: For continuous features such as age, resting blood pressure, cholesterol, and maximum heart rate
- **Bar charts**: For categorical variables like sex, chest pain type, fasting blood sugar, etc.
- **Correlation heatmap**: To analyze relationships between all numerical features
- **Target variable distribution**: To visualize class balance (presence/absence of heart disease)

---

## 💡 Insights

- Certain chest pain types are more frequently associated with heart disease
- Males seem to have a higher incidence of heart disease in this dataset
- Some variables, like thalassemia and exercise-induced angina, show strong visual relationships with the target variable
- The dataset is relatively balanced in terms of heart disease classification, making it suitable for predictive modeling

---

## 📌 Conclusion

This analysis lays a solid foundation for building classification models to predict the presence of heart disease. By understanding data distributions and feature relationships, we can make informed decisions in selecting features and preprocessing steps for modeling

---

## 🔍 Next Steps

- Perform feature engineering
- Apply machine learning models for classification
- Evaluate model performance with accuracy, precision, recall, and F1-score
