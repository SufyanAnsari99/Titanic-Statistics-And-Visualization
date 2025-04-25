# Titanic-Statistics-And-Visualization
Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries like Pandas, Seaborn, and Matplotlib. Includes summary statistics, visualizations (boxplots, histograms, heatmaps), and insights into survival patterns based on features like gender, class, and age.
# Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Objective
The goal of this task was to understand the Titanic dataset through Exploratory Data Analysis (EDA) using statistics and visualizations.

---

## 📊 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Dataset
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

---

## 🔍 Steps Performed

1. **Loaded the dataset** using Pandas.
2. **Summary statistics** generated using `.describe()`.
3. **Data cleaning:**
   - Handled missing values in `Age` and `Embarked`.
4. **Visualizations:**
   - Histograms for numeric distributions.
   - Boxplots for detecting outliers.
   - Countplots to explore categorical relationships with survival.
   - Heatmap for correlation matrix.
   - Pairplot for feature comparison.
5. **Statistical Analysis:**
   - Checked for skewness in numeric columns.
   - Reviewed multicollinearity using correlation values.

---

## 📈 Key Insights

- Females had a higher survival rate than males.
- Passengers in 1st class were more likely to survive.
- Age and Fare had some skewness and outliers.
- Strong negative correlation between `Pclass` and `Survived`.

---

## 📂 Files in Repository

- `Titanic-Dataset.csv` - Dataset
- `eda_titanic.py` - EDA script
- `README.md` - This file

---

## ✅ Conclusion
This EDA helped uncover patterns and prepare the dataset for further machine learning tasks. Visualizations played a critical role in understanding data distribution and relationships.

