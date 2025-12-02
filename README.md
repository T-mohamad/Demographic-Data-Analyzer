# Demographic-Data-Analyzer


This project analyzes demographic data extracted from the **1994 U.S. Census database** using **Pandas**.  
It is part of the freeCodeCamp Data Analysis with Python certification.

---

## 📊 Project Overview
The dataset contains demographic information such as age, workclass, education, occupation, race, sex, hours worked per week, native country, and salary.  
The goal is to answer several demographic questions using Pandas.

---

## ✅ Questions Answered
The script calculates:

1. Number of people of each race (`race` column).
2. Average age of men.
3. Percentage of people with a Bachelor's degree.
4. Percentage of people with advanced education (Bachelors, Masters, Doctorate) earning >50K.
5. Percentage of people without advanced education earning >50K.
6. Minimum number of hours worked per week.
7. Percentage of people working minimum hours per week earning >50K.
8. Country with the highest percentage of >50K earners and that percentage.
9. Most popular occupation for >50K earners in India.

---

## 🛠️ Files
- **`demographic_data_analyzer.py`** → Main script with Pandas calculations.
- **`main.py`** → Used to run and test the analyzer interactively.
- **`test_module.py`** → Unit tests to validate your implementation.
- **`adult.data.csv`** → Dataset file (from UCI Machine Learning Repository).

---

## 🚀 How to Run
1. Clone this repository or download the files.
2. Install dependencies:
   ```bash
   pip install pandas
