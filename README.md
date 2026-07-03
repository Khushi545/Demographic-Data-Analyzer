
# 📊 Demographic Data Analyzer with Pandas

A data analysis project using **Python** and **Pandas** to analyze demographic data
extracted from the **1994 Census database (UCI Machine Learning Repository)**.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Questions Answered](#questions-answered)
- [Sample Output](#sample-output)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Test Results](#test-results)
- [Dataset Source](#dataset-source)
- [Author](#author)

---

## 🔍 Overview

This project uses **Pandas** to explore and analyze a real-world census dataset.
It answers 9 key demographic questions about race, education, salary, work hours,
and occupations across different countries.

---

## 📂 Dataset

The dataset contains **48,842 rows** of census data with the following columns:

| Column | Description |
|--------|-------------|
| `age` | Age of the individual |
| `workclass` | Type of employer |
| `fnlwgt` | Final weight |
| `education` | Highest education level |
| `education-num` | Education level as a number |
| `marital-status` | Marital status |
| `occupation` | Type of occupation |
| `relationship` | Relationship status |
| `race` | Race of the individual |
| `sex` | Gender |
| `capital-gain` | Capital gain |
| `capital-loss` | Capital loss |
| `hours-per-week` | Hours worked per week |
| `native-country` | Country of origin |
| `salary` | Whether salary is >50K or <=50K |

---

## ❓ Questions Answered

1. How many people of each race are represented in the dataset?
2. What is the average age of men?
3. What percentage of people have a Bachelor's degree?
4. What percentage of people **with** advanced education (Bachelors, Masters, Doctorate) earn >50K?
5. What percentage of people **without** advanced education earn >50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of people who work the minimum hours earn >50K?
8. Which country has the highest percentage of people earning >50K?
9. What is the most popular occupation for those earning >50K in **India**?

---

## 📈 Sample Output

```
Number of each race:
 White                 27816
 Black                  3124
 Asian-Pac-Islander     1039
 Amer-Indian-Eskimo      311
 Other                   271
Name: race, dtype: int64

Average age of men: 39.4

Percentage with Bachelors degrees: 16.4%

Percentage with higher education that earn >50K: 46.5%

Percentage without higher education that earn >50K: 17.4%

Min work time: 1 hours/week

Percentage of rich among those who work fewest hours: 10.0%

Country with highest percentage of rich: Iran

Highest percentage of rich people in country: 41.9%

Top occupations in India: Prof-specialty
```

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?logo=numpy)

- **Python 3**
- **Pandas** — data loading, filtering, grouping, aggregation
- **NumPy** — numerical operations

---

## 📁 Project Structure

```
Demographic-Data-Analyzer/
│
├── demographic_data_analyzer.py   # Main analysis code
├── main.py                        # Run and test the project
├── test_module.py                 # Unit tests
├── adult.data.csv                 # 1994 Census dataset
└── README.md                      # Project documentation
```

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/khushikhatri520/Demographic-Data-Analyzer.git
cd Demographic-Data-Analyzer
```

### 2. Install dependencies
```bash
pip install pandas numpy
```

### 3. Run the project
```bash
python main.py
```

---

## ✅ Test Results

```
.......... 
----------------------------------------------------------------------
Ran 10 tests in 1.234s

OK — All 10 unit tests passed ✅
```

---

## 🔑 Key Insights from the Data

- 🌍 **White** is the most represented race with 27,816 people
- 👨 Average age of men is **39.4 years**
- 🎓 Only **16.4%** of people have a Bachelor's degree
- 💰 People with advanced education are **~3x more likely** to earn >50K
- 🕐 Some people work as little as **1 hour per week**
- 🇮🇷 **Iran** has the highest percentage of high earners at **41.9%**
- 🇮🇳 In India, **Prof-specialty** is the top occupation among high earners

---

## 📚 Dataset Source

> Dua, D. and Graff, C. (2019). UCI Machine Learning Repository.
> Irvine, CA: University of California, School of Information and Computer Science.

---
