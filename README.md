# 📊 Nobel Prize Data Analysis

This project is a data exploration and analysis of the Nobel Prize dataset using Python, pandas, seaborn, and NumPy.

## 📁 Dataset

The dataset used in this project is `nobel.csv`, which includes information about Nobel Prize laureates from the early 1900s to recent years. It contains fields such as:

- `full_name`
- `sex`
- `birth_country`
- `year`
- `category`

## 🧠 Objectives

The goal of this project was to analyze the dataset and answer a series of insightful questions, including:

1. **Most commonly awarded gender and birth country**
2. **Decade with the highest ratio of US-born Nobel Prize winners**
3. **Decade and category with the highest proportion of female laureates**
4. **Identify the first woman to win a Nobel Prize and in which category**
5. **List individuals or organizations who won more than one Nobel Prize**

## ✅ What I Did

- Loaded and cleaned the data using `pandas`
- Created new features such as `female_winners`, `Us_born_winners`, and `decade`
- Used `groupby`, `value_counts`, and logical filtering to extract insights
- Visualized trends using `seaborn.relplot()` to show:
  - Proportion of female winners over time by category
  - Proportion of US-born winners by decade
- Sorted and filtered the data to:
  - Identify the most frequent gender and country
  - Find the top female representation by decade and category
  - Extract repeat Nobel Prize winners
  - Locate the first woman laureate

## 📌 Key Results

- Most common gender: `Male`
- Most common birth country: `United States of America`
- Highest ratio of US-born winners: `Decade = 2000s` (or specific decade found)
- Highest proportion of female laureates: `{'decade': 2020, 'category': 'Literature'}`
- First woman to win a Nobel Prize: `Marie Curie` in `Physics`
- Repeat winners include: `Marie Curie`, `Linus Pauling`, `International Committee of the Red Cross`, and more.

## 🧪 Technologies Used

- Python 3
- pandas
- seaborn
- NumPy
- Jupyter Notebook

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nobel-prize-analysis.git
   cd nobel-prize-analysis
