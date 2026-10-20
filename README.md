# CodeAlpha Internship - Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs comprehensive Exploratory Data Analysis (EDA) on the Titanic dataset as part of the CodeAlpha Data Analytics Internship. The goal is to inspect data structures, handle missing values, detect anomalies, and validate key statistical hypotheses regarding passenger survival.

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** - Data manipulation, inspection, and cleaning
- **NumPy** - Numerical operations

## 🔍 Key Steps & Analysis Performed
1. **Data Loading & Structure Inspection:** Inspected dataframe dimensions, column types, and structural integrity using `info()`.
2. **Data Quality Checks:** Scanned for missing values and verified duplicate records.
3. **Data Cleaning & Anomaly Handling:** Imputed missing values for `Age` (using median) and `Embarked` (using mode), while addressing high-missingness columns like `Cabin`. Detected outliers in ticket fares using the Interquartile Range (IQR) method.
4. **Statistical Hypothesis Validation:** Calculated overall passenger survival rates and generated targeted groupby metrics across gender and passenger classes.

## 🚀 How to Run the Code
1. Ensure you have Python installed with pandas and numpy:
   ```bash
   pip install pandas numpy
