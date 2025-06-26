# 📊 Week 6: Exploratory Data Analysis (EDA) – Summary

This week focused on building strong data exploration skills using Python. I explored real-world datasets, applied visualizations, discovered correlations, engineered features, and practiced on a Kaggle dataset.

---

## 🗓️ Weekly Breakdown

### 📌 Day 1: Visualization Basics
- Learned basic plotting with **Matplotlib** and **Seaborn**
- Types of plots explored:
  - Histogram
  - Bar plot
  - Box plot
  - Count plot
  - Pie chart
  - Line plot
  - Heatmap
  - Scatter plot
- ✅ Understood how to identify outliers and distributions visually.

---

### 📌 Day 2: Correlation Analysis
- Used `.corr()` and `sns.heatmap()` to explore relationships between numeric features.
- Learned:
  - Positive vs. Negative correlation
  - Multicollinearity risks
- ✅ Identified highly correlated features for further analysis or removal.

---

### 📌 Day 3: Pair Plots & Advanced Visualization
- Used `sns.pairplot()` to visualize relationships and distributions in one grid.
- Observed:
  - Histograms on diagonal → show distribution of single variables
  - Scatter plots on off-diagonal → show relationships between features
- ✅ Learned how to read patterns, clustering, and separation visually.

---

### 📌 Day 4: Case Study – Iris Dataset
- Performed full EDA on the Iris dataset
- Explored:
  - Violin plots for distribution across species
  - Created new binned features like petal_length_binned
- ✅ Understood class-wise distributions and separation of features.

---

### 📌 Day 5: Feature Engineering Basics
- Techniques explored:
  - Binning continuous features into categories (short, medium, long petals)
  - Creating interaction features (e.g. petal_length × petal_width)
  - Mapping and transformation
- ✅ Strengthened skills in deriving new insights from raw features.

---

### 📌 Day 6: Kaggle EDA Practice – Airline Customer Dataset
- Worked with a real-world customer dataset.
- Steps followed:
  1. Basic Data Understanding
  2. Handling Missing Values
  3. ✅ Univariate Analysis
     - AGE, FFP_TIER, WORK_COUNTRY, FLIGHT_COUNT, SEG_KM_SUM, Points_Sum, SUM_YR_1, SUM_YR_2, avg_discount
  4. ✅ Bivariate Analysis
     - AGE vs Points_Sum (scatter)
     - avg_discount vs Points_Sum (scatter)
     - FFP_TIER vs SEG_KM_SUM (boxplot)
     - GENDER vs Points_Sum (boxplot)
     - Correlation heatmap
  5. ✅ Feature Engineering
     - Created segments like:
       - Loyal Customers
       - Young Frequent Flyers
       - Infrequent Travelers

---

### 📌 Day 7: Recap + EDA Quiz
- Completed a 5-question quiz on:
  - Choosing the right plot
  - Understanding correlation
  - Outliers and distributions
- ✅ Scored 5/5 🎉
- Reinforced:
  - When to use boxplot vs scatterplot
  - How to interpret correlation heatmaps

---

## 💡 Key Takeaways

| Task                             | Skill Gained                                       |
|----------------------------------|----------------------------------------------------|
| Univariate Analysis              | Distribution, outliers, skewness                   |
| Bivariate Analysis               | Relationships between features                     |
| Feature Engineering              | Created useful new columns                         |
| Visual Communication             | Chose the right plot for the right situation       |
| Real-World Practice              | Used airline dataset to simulate industry problems |

---

### ✅ Tools Used
- Python 🐍
- Pandas 🐼
- Matplotlib 📊
- Seaborn 🌊
- Jupyter Notebooks 📒
- GitHub 🌐

---

### 🚀 What's Next?
📁 Machine Learning Basics.

