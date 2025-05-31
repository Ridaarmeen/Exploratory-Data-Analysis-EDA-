🚢 Titanic Dataset - Exploratory Data Analysis (EDA)
-This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries like Pandas, Seaborn, Matplotlib, and Plotly.

📊 Objectives
- Understand the structure and contents of the Titanic dataset
- Use descriptive statistics and visualizations to explore data
- Identify patterns related to survival, class, age, gender, and fare
- Detect outliers and class imbalance
- Provide insights for potential machine learning modeling

🔍 Key Exploratory Steps

- Data Overview: `.info()`, `.describe()`, checking null values
- Visualizations:
  - Correlation heatmaps
  - Countplots for gender, class, survival
  - Boxplots for outlier detection
  - Distribution plots for Age and Fare
- Pattern Recognition:
  - Higher survival rate for females and 1st class passengers
  - Age and fare show outliers and skewed distributions
  - Mild class imbalance (more passengers died than survived)

📌 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly` _(optional/interactive)_

📈 Sample Insights
- Survival rate is higher among:
  - Females
  - 1st class passengers
  - Younger children
- Fare and Pclass are strongly related: higher fare usually means 1st class
- Age and Fare have outliers and skewed distributions
