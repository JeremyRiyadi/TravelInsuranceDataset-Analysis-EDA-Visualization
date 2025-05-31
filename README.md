### 🧠 Travel Insurance Prediction - Exploratory Data Analysis & Preprocessing

This project performs **exploratory data analysis (EDA)** and **preprocessing** on a customer dataset aimed at understanding and preparing the data for modeling the `Stage` variable. The dataset includes various demographic and behavioral attributes relevant to customer segmentation and lifecycle stages.

---

### 🎯 Main Objectives

* Clean and prepare data for machine learning
* Explore numerical and categorical features
* Identify missing values and outliers
* Understand feature distributions and relationships
* Encode and normalize data
* Prepare a clean dataset for modeling the `Stage` classification

---

### 🛠 Tools & Libraries Used

* **Python 3**
* **Pandas** for data manipulation
* **Matplotlib** and **Seaborn** for data visualization
* **NumPy** for numerical operations
* **Scikit-learn** for preprocessing
* **Jupyter Notebook / Google Colab** for code execution and visualization

---

### 📊 Key Steps & Visualizations

* **Dataset Overview**: Summary of missing values, dtypes, and basic stats
* **Univariate Analysis**:

  * Boxplots for numerical features (e.g., `Revenue`, `Tenure`)
  * Countplots for categorical features (e.g., `Gender`, `Country`, `Product`)
* **Bivariate Analysis**:

  * Correlation heatmap to identify multicollinearity
  * Grouped bar plots comparing feature distribution across `Stage`
* **Outlier Detection**:

  * Boxplots to detect extreme values in numeric variables
* **Handling Missing Values**:

  * Identification and imputation/cleaning strategies
* **Data Encoding**:

  * Label Encoding for target variable
  * One-hot encoding for categorical predictors
* **Final Dataset Preparation**:

  * Clean, encoded dataset ready for modeling tasks

---

### 🧩 Dataset Target: `Stage`

The variable `Stage` represents the customer's current position in the lifecycle. This project aims to understand how various features influence or relate to different stages before applying any predictive modeling technique.

---

### 📌 Conclusion

This notebook establishes a robust foundation for the next steps in the machine learning workflow, including:

* Feature selection
* Model training (e.g., XGBoost, Random Forest, etc.)
* Evaluation of classification performance

Proper understanding and preprocessing of the dataset is crucial for developing an effective and interpretable model.
