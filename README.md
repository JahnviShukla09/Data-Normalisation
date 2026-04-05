
# 📊 STUDY OF DATA NORMALIZATION AND CATEGORICAL ENCODING USING PYTHON

Name – Jahnvi Shukla <br/>
Branch – ENTC A3 <br/>
PRN – 25070123055 <br/>

---

## 🎯 Aim

To study and perform **data normalization techniques and encoding of categorical variables using Python**.

---

## 📘 Introduction

In data analysis and machine learning, datasets often contain **numerical values with different scales and categorical variables**. These can affect the performance of models and analysis.

**Data normalization** is used to scale numerical values into a common range, while **categorical encoding** converts non-numeric data into numerical form so that it can be processed by algorithms.

Python libraries like **Pandas, NumPy, and Scikit-learn** provide efficient methods to perform these operations.

---

## 📚 Theory

**Data normalization** is the process of scaling numerical values into a standard range so that no single feature dominates others. It improves the performance of machine learning models and ensures fair comparison between variables.

There are different types of normalization techniques:

**1. Min-Max Normalization:**
This method scales data between 0 and 1 using the formula:
[
(x - min) / (max - min)
]
It is useful when the data does not contain extreme outliers.

**2. Z-Score Normalization:**
This method standardizes data based on mean and standard deviation:
[
(x - mean) / std
]
It is useful when the dataset contains outliers.

**3. Decimal Scaling:**
This method scales values by dividing by powers of 10 to bring them into a smaller range.

Normalization can also be applied to **multiple columns simultaneously** using Pandas operations.

---

### Categorical Encoding

Categorical variables cannot be directly used in numerical analysis, so they are converted into numbers using encoding techniques:

**1. Label Encoding:**
Assigns a unique number to each category (e.g., Male = 1, Female = 0).

**2. One-Hot Encoding:**
Creates separate binary columns for each category using `pd.get_dummies()`.

**3. Dummy Encoding:**
Similar to one-hot encoding but drops one column to avoid redundancy.

These techniques help convert categorical data into a format suitable for analysis and machine learning.

---

## ⚙️ Procedure

1. Import **Pandas, NumPy, and sklearn libraries**.
2. Create a dataset containing numerical and categorical data.
3. Apply **Min-Max normalization** on numerical columns.
4. Apply **Z-score normalization** using mean and standard deviation.
5. Perform **decimal scaling** on numerical data.
6. Normalize multiple columns together.
7. Create a dataset with categorical variables.
8. Apply **Label Encoding** using `LabelEncoder`.
9. Apply **One-Hot Encoding** using `pd.get_dummies()`.
10. Apply **Dummy Encoding** by dropping one column.
11. Load a larger dataset (Amazon dataset).
12. Apply normalization techniques on price and rating.
13. Analyze the transformed dataset.

---

## 📊 Observations / Result

* Price values were successfully scaled between **0 and 1 using Min-Max normalization**.
* Units sold were standardized using **Z-score normalization**.
* Decimal scaling reduced large numerical values.
* Multiple columns were normalized simultaneously.

For categorical data:

* Gender was encoded using **Label Encoding** (Male = 1, Female = 0).
* Payment method was converted into binary columns using **One-Hot Encoding**.
* Dummy encoding reduced redundancy.

In large dataset:

* Price and Rating were normalized effectively.

Final dataset became **scaled, consistent, and suitable for machine learning and analysis**.

---

## 🛠️ Tools / Libraries Used

* Python
* Google Colab / Jupyter Notebook
* Pandas Library
* NumPy Library
* Scikit-learn

---

## 💡 Applications

* Machine learning preprocessing
* Data scaling for better model performance
* Converting categorical data into usable format
* Data science and analytics
* Business and customer data analysis

---

## ✅ Advantages

1. Improves accuracy of machine learning models
2. Ensures all features are on the same scale
3. Prevents bias due to large values
4. Converts categorical data into numerical form
5. Makes data suitable for algorithms
6. Enhances data consistency and usability

---

## 🏁 Conclusion

Data normalization and categorical encoding are essential preprocessing techniques in data analysis and machine learning. Normalization helps in scaling numerical data, while encoding converts categorical data into numerical format. Using Python libraries like Pandas and Scikit-learn, these operations can be performed efficiently, making the dataset ready for analysis and modeling.
