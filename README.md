# Project-2-Python-For-Data-Analysis-BadDrivers
End-to-end EDA project on the FiveThirtyEight Bad Drivers dataset | Analyzing fatal collision patterns across U.S. states using Python, Pandas, Matplotlib &amp; Seaborn

# 🚗 Exploratory Data Analysis — Bad Drivers Dataset

A structured EDA project on the **Bad Drivers** dataset from FiveThirtyEight, completed as part of the **Python for Data Analysis** course.

## 📌 Objective
Explore fatal collision patterns across U.S. states and uncover key relationships between speeding, alcohol impairment, insurance premiums, and accident rates.

## 📂 Dataset
- **Source:** FiveThirtyEight — [bad-drivers.csv](https://github.com/fivethirtyeight/data/tree/master/bad-drivers)
- **Records:** 51 U.S. states
- **Features:** fatal_collisions, pct_speeding, pct_alcohol, pct_not_distracted, pct_no_prev_accidents, insurance_premium, insurance_losses

## 🛠️ Tools & Libraries
| Library | Purpose |
|---|---|
| Pandas | Data loading, cleaning, and exploration |
| NumPy | Numerical operations |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualizations |

## 📊 Analysis Structure
1. Imports & Setup
2. Load Dataset
3. Rename Columns
4. First Look (head / tail)
5. Data Structure & Info
6. Missing Values Check
7. Descriptive Statistics
8. Feature Engineering — Speed Level
9. Univariate Analysis — Numerical
10. Univariate Analysis — Categorical
11. Bivariate Analysis — Numerical vs Numerical
12. Bivariate Analysis — Numerical vs Categorical
13. Multivariate Analysis
14. Correlation Heatmap
15. Pairplot
16. Key Insights

## 💡 Key Insights
- Speeding alone is not the strongest predictor of fatal collisions — alcohol impairment shows a clearer impact
- North Dakota and South Carolina are clear outliers with the highest fatal collision rates
- Insurance premiums don't always reflect actual collision rates — pricing involves more complex factors
- Fatal collision distribution is right-skewed — most states fall between 10–20 collisions per billion miles
- Medium-speed states show the highest variance in collision rates

## 🚀 How to Run
```bash
git clone https://github.com/ammarelsayed-2a/Project-2-Python-For-Data-Analysis-BadDrivers.git
cd Project 2 Python-For-Data-Analysis-BadDrivers
jupyter notebook "Project 2 BadDrivers.ipynb"
```

## 👤 Author
**Ammar Elsayed** — Python for Data Analysis | 2026  
[LinkedIn](https://www.linkedin.com/in/ammar-elsayed-ibrahim)
