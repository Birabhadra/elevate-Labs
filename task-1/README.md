# 🧹 AI & ML Internship Task 1: Data Cleaning & Preprocessing

## 📌 Objective
The objective of this task is to learn how to clean and preprocess raw data in preparation for machine learning models. I have used the Titanic dataset for this task.

---

## 🛠 Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Steps Performed

### 1. Data Import & Exploration
- Loaded the Titanic dataset
- Explored data types and checked for null values

### 2. Handling Missing Values
- Filled missing `Age` values using the **median**
- Filled missing `Embarked` values using the **mode**

### 3. Encoding Categorical Features
- Applied **one-hot encoding** on `Sex` and `Embarked` columns

### 4. Feature Scaling
- Used **StandardScaler** to standardize `Age` and `Fare` columns

### 5. Outlier Detection & Removal
- Used **boxplots** to visualize outliers in `Fare` and `Age`
- Removed outliers using the **IQR method**

### 6. Final Preparation
- Dropped unnecessary columns like `Name`, `Ticket`, `Cabin`
- Split data into features (`X`) and target (`y`)
- Performed a train-test split

---

## 📊 Output
- A cleaned and preprocessed dataset ready for training ML models.
- Train-test split completed and saved in variables: `X_train`, `X_test`, `y_train`, `y_test`.

---

## ❓ Interview Questions Practiced
1. What are the different types of missing data?
2. How do you handle categorical variables?
3. What is the difference between normalization and standardization?
4. How do you detect outliers?
5. Why is preprocessing important in ML?
6. What is one-hot encoding vs label encoding?
7. How do you handle data imbalance?
8. Can preprocessing affect model accuracy?

---

## 📁 Folder Contents
- `notebook.ipynb`: Jupyter notebook with full code
- `Titanic-Dataset.csv`: Dataset used
- `titanic_cleaned.csv `:cleaned dataset ready to use
- `README.md`: This file

---

## ✅ Submission
- GitHub Repo: [Insert your repo link here]
