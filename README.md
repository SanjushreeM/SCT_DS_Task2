# SCT_DS_Task2 - Titanic Dataset EDA

## 📌 Project Overview

This project is part of the **SkillCraft Technology Internship – Task 02**.  
The objective of this task is to perform **Data Cleaning and Exploratory Data Analysis (EDA)** on a dataset of choice.  
For this project, the **Titanic Dataset from Kaggle** is used to explore relationships between variables and identify patterns and trends in the data.

---

## 🎯 Task Objective

- Perform data cleaning on the dataset
- Handle missing values
- Explore relationships between variables
- Visualize patterns and trends using plots
- Draw meaningful insights from the data

---

## 🧹 Data Cleaning Steps

The following data cleaning steps were performed:

- Removed columns with excessive missing values (`Cabin`)
- Filled missing `Age` values using median
- Filled missing `Embarked` values using mode
- Converted categorical columns into appropriate data types
- Checked for null values after cleaning

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations and analyses were performed:

- Overall survival count
- Survival rate by Gender
- Survival rate by Passenger Class
- Age distribution of passengers
- Fare distribution
- Survival based on Embarkation Port
- Family size vs Survival
- Correlation Heatmap of numerical features

---

## 🔍 Key Insights

- Female passengers had a significantly higher survival rate than males.
- First-class passengers were more likely to survive than second and third class.
- Passengers who paid higher fares had better survival chances.
- Children showed slightly higher survival rates compared to adults.
- Small families had better survival rates than solo or large families.
- Embarkation port influenced survival probability.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab  

---

## 📁 Files Included

`SCT_DS_Task2.ipynb` — Complete code, analysis, and visualizations

## 📦 Requirements**
Install dependencies using:
`pip install -r requirement.txt`
Recommended versions (for reproducibility):
- pandas >= 1.5.0
- numpy >= 1.25.0 
- seaborn >= 0.12.0 
- matplotlib >= 3.7.0

---

## 📂 Dataset Used

**Dataset:** Titanic Dataset  
**Source:** Kaggle Titanic Competition Dataset ([Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data))  
**File Used:** `train.csv`

The dataset contains passenger details such as:
- Passenger Class
- Name, Age, Gender
- Ticket Fare
- Cabin
- Embarkation Port
- Survival Status


## ▶️ How to Run**
1. Clone the repository:
    `git clone https://github.com/SanjushreeM/SCT_DS_Task2.git`
2. Open `SCT_DS_Task2.ipynb` in Jupyter Notebook or Google Colab
3. Install dependencies:
     `pip install -r requirement.txt`
5. Run each notebook cell sequentially
