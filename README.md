# 📊 Assignment 1 – Data Exploration and Cleaning Using Pandas

## 📌 Objective
The objective of this project is to perform basic data exploration and data cleaning operations using Python and the Pandas library.

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas 📊
- Jupyter Notebook 📒
- VS Code 💻

---

## 📂 Dataset Features
The dataset contains employee-related information such as:
- Education
- Joining Year
- City
- Payment Tier
- Age
- Gender
- Experience
- Leave Status

---

## ✨ Tasks Performed
✔ Loaded CSV dataset into Pandas DataFrame  
✔ Explored dataset using head(), shape, info(), and columns  
✔ Checked and handled missing values  
✔ Removed duplicate records  
✔ Filtered data using conditions  
✔ Selected required columns  
✔ Created derived column (`Experience_Age_Ratio`)  
✔ Saved cleaned dataset as CSV file  

---

## 📈 Derived Column
Created a new column:

```python
Experience_Age_Ratio = ExperienceInCurrentDomain / Age
