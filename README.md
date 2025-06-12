# titanic-eda-kulsoom
Exploratory Data Analysis of Titanic dataset using Python
# 🚢 Titanic EDA – Survival Analysis

This project performs exploratory data analysis (EDA) on the Titanic dataset to uncover patterns related to passenger survival using Python and data visualization tools.

---

## 📊 What I Did

- Cleaned missing data (`Age`, `Embarked`), dropped unusable column (`Cabin`)
- Explored survival trends based on gender, passenger class, age, and fare
- Applied **log transformation** to `Fare` to handle skewed distribution and outliers
- Created a new feature: `FamilySize = SibSp + Parch + 1`
- Plotted **survival rates by family size** — revealed small families had better outcomes
- Visualized **age distribution** and identified concentration in the 20–40 range
- Converted numerical columns to categorical (e.g., `Survived`, `Pclass`) for clean plots
- Used **countplots**, **histograms**, and **boxplots** to extract patterns

---

## 🛠️ Tools Used

- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

---

## ✅ Key Insights

- **Females** and **first-class** passengers had the highest survival rate
- **Passengers who paid higher fares** were more likely to survive
- **Small families (2–4)** survived more often than solo or large groups
- **Solo travelers** had the lowest survival rate
- Survival correlated with **multiple features**, not just one (e.g., class + gender + group size)

---

## 📁 File

- `Titanic_EDA_Kulsoom.ipynb` – Full notebook with step-by-step explanations, plots, and interpretations
