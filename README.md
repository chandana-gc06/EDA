#  COVID-19 Exploratory Data Analysis (EDA)
This project presents an in-depth Exploratory Data Analysis (EDA) on a COVID-19 dataset, using Python and Jupyter Notebook. The goal is to analyze COVID patient data in terms of age, sex, medical conditions, ICU admissions, intubations, comorbidities, and deaths — and to visualize key patterns with clear, interpretable charts.

This project was completed as part of a data analysis internship task.


---

## 📁 Project Structure

CodeAlpha_EDA-MAIN
│
├── notebooks/
│   ├── task2.ipynb   
│   └── Covid Data.csv         # COVID dataset used in the project
│
├── images/                    # Folder containing all saved plots
│
├── requirements.txt           # Python libraries used
└── README.md                  # Project description and instructions


---

## 📌 Dataset

Source: COVID-19 public health patient data

Format: CSV

Details: Includes patient-level data with attributes like:

AGE, SEX, ICU, INTUBED, PNEUMONIA

Various comorbidities (e.g., DIABETES, OBESITY)

DATE_DIED, CLASIFFICATION_FINAL (final COVID classification)
---

## 🎯 Objectives

-Explore and understand the structure of the dataset

-Clean missing and inconsistent data

-Analyze patient demographics and conditions

-Identify patterns in ICU admission, intubation, and mortality

-Visualize insights using Seaborn and Matplotlib

-Save all plots as .png for reporting and presentations

---

## 📊 Visualizations

All charts are saved in the `images/` folder:

| Chart Title                      | File Name                              |
|----------------------------------|----------------------------------------|
| Sex Count    | `Sex Count.png`          |
| ICU Cases      | `ICU Cases.png`|
| Classification           | `Classification.png`              |
| Boxplot of AGE      | `Boxplot of AGE .png`     |
| Boxplot of AGE by SEX      | `Boxplot of AGE by SEX.png`            |
| Boxplot of AGE by ICU status     | `Boxplot of AGE by ICU status .png`    |
| Correlation Heatmap              | `Correlation Heatmap.png`        |

---

## 🧪 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data handling
- **NumPy** – Numerical operations
- **Seaborn & Matplotlib** – Visualizations

---

## 🚀 How to Run the Project

1. **Clone the repository** or download the ZIP:
   ```bash
    https://github.com/chandana-gc06/EDA
