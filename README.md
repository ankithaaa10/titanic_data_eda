# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand feature distributions, relationships, and patterns that may influence passenger survival.

---

Objective
To explore the Titanic dataset using statistics and visualizations in order to:
- Detect missing values and data distributions
- Identify trends and patterns across features
- Understand relationships between features (especially with survival)
- Prepare the dataset for further machine learning tasks

---

Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (for optional interactive plots)

---

Key EDA Steps Covered

1. Summary Statistics
Generated `.describe()` output to understand:
- Mean, median, standard deviation, percentiles
- Data ranges and feature distributions

2. Histograms
Visualized numerical features like:
- `Age`, `Fare`, `SibSp`, and `Parch`  
to understand their skewness and spread.

3. Boxplots
Used to detect outliers in numerical columns:
- Found outliers in `Fare` and `Age`.

4. Correlation Matrix
Created a heatmap to visualize correlations between:
- `Age`, `Fare`, `SibSp`, `Parch`, and `Survived`.

5. Pairplot
Explored pairwise relationships and patterns in survival across numeric features.

6. Countplots
Visualized categorical distributions and survival patterns by:
- `Sex`, `Pclass`, `Embarked`, and `Survived`.

Observations

- Gender: Females had higher survival rates than males.
- Class: Passengers in 1st class had better survival chances.
- Fare: Higher fare passengers were more likely to survive.
- Age: Children and younger passengers had slightly better survival odds.
- Correlation: `SibSp` and `Parch` showed moderate correlation.





