# 🚢 Titanic Survival Data Analysis - Exploratory Data Analysis (EDA)

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the Titanic dataset (`train.csv`) to uncover patterns and insights related to passenger survival. The analysis uses visual and statistical techniques to identify key trends, relationships, and anomalies in the data.

---

## 📁 Dataset

- **File Name**: `train.csv`
- **Description**: Classic Titanic passenger dataset containing features like:
  - Passenger class, gender, age, fare, number of siblings/spouses aboard, port of embarkation, etc.
- **Target Variable**: `Survived` (0 = Did not survive, 1 = Survived)

---

## 🛠 Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 📊 EDA Techniques Used

- Descriptive statistics: `.describe()`, `.info()`, `.value_counts()`
- Visualization:
  - Count plots for categorical variables
  - Histograms and boxplots for continuous variables
  - Pairplots and heatmaps for correlations
  - Custom age grouping using `pd.cut()`
  - Bar plots for survival rates across groups (age, sex, class, etc.)

---

## 📈 Key Insights and Conclusion

- **Gender**: Females had a significantly higher survival rate (~74%) than males (~19%).
- **Class**: 1st class passengers had the highest survival rate. Survival dropped significantly in 2nd and 3rd class.
- **Age**: Children (≤12 years) had better chances of survival than adults and seniors.
- **Fare**: Higher fare paid was positively correlated with higher survival.
- **Port of Embarkation**: Cherbourg (C) passengers showed a higher survival rate.
- **Family Size**: Smaller families (1–2 members) survived more frequently.
- **Missing Data**: Notable in the 'Cabin' column; age-related missing values were handled using grouping and binning.

➡️ **Conclusion**: Survival on the Titanic was influenced significantly by **social and demographic factors** — especially gender, class, and age.

---

## 🚀 How to Run

1. Clone this repository or download the files.
2. Ensure Python and Jupyter Notebook are installed.
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
