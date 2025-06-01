# 🧼 Task 1: Data Cleaning & Preprocessing – AI & ML Internship

## 📌 Objective
To learn how to clean and prepare raw data for machine learning using the Titanic dataset.

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## 📁 Dataset
The dataset used for this task is the classic **Titanic dataset**, which contains information about passengers on the Titanic, including their age, sex, ticket class, and survival status.

## 🧪 Steps Performed

1. **Data Loading & Exploration**
   - Loaded the CSV using `pandas`
   - Explored the shape, column types, and missing values

2. **Handling Missing Values**
   - Filled missing `Age` values with the median
   - Filled missing `Embarked` values with the mode
   - Dropped `Cabin` column due to excessive missing values

3. **Encoding Categorical Variables**
   - Applied Label Encoding to `Sex` and `Embarked`
   - Dropped `Name` and `Ticket` columns as they are not useful for modeling

4. **Feature Scaling**
   - Applied StandardScaler to `Age` and `Fare` for standardization

5. **Outlier Detection**
   - Used boxplots to visualize outliers

6. **Final Output**
   - Saved the cleaned data to `Cleaned_Titanic_Dataset.csv`


## 📂 Files in Repo
- `Titanic-Dataset.csv` – Original dataset
- `Cleaned_Titanic_Dataset.csv` – Final cleaned dataset
- `Titanic_Preprocessing` – Your Python script or notebook
- `README.md` – This file

## 🙋‍♂️ Author
MOHAMMED MUJAHED – AI & ML Internship Participant
