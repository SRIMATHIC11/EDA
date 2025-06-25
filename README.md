  **EXPLORATORY DATA ANALYSIS**-Titanic dataset

Welcome to my mini-project on **Titanic Survival Analysis using EDA**!  
This project explores the famous Titanic dataset through data cleaning, statistics, and visualizations.

EDA is the foundation of any data science task—understanding your data is the first step to building great models.

---

 Project Structure


elevate-task/
├── eda_titanic.py     # Python script to perform data analysis & visualizations
├── titanic.csv        # The dataset used for this task
├── README.md          # Project overview and instructions


---

Dataset Overview

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Samples**: ~891 (standard training dataset)  
- **Target column**: `Survived` (0 = No, 1 = Yes)  
- **Features**: `Pclass`, `Age`, `Sex`, `Fare`, `SibSp`, `Parch`, etc.

Each row represents a passenger with details like class, age, fare, family aboard, and survival status.

---

What the Script Does

`eda_titanic.py` performs:

- Loads the Titanic dataset  
- Displays dataset info, missing values, and summary stats  
- Visualizes:
  - Age distribution (histogram)
  - Boxplot of Age by Survival
  - Correlation heatmap for numeric features
  - Pairplot to observe feature relationships

---

 Sample Output (What You’ll See)

- Cleaned DataFrame with basic stats  
- Missing value count  
- Histograms and boxplots  
- A heatmap showing feature correlations  
- Pairplot showing survival-related patterns

---

 How to Run

1. Activate your environment:

```bash
# Linux/Mac
source venv/bin/activate

# Windows
venv\Scripts\activate.bat
```

2. Install required libraries:

```bash
pip install pandas matplotlib seaborn
```

3. Run the script:

```bash
python eda_titanic.py
```

---

 Insights You May Discover

- Younger passengers had a higher survival rate  
- Females were more likely to survive  
- 1st class passengers had better survival chances  
- Fare and Pclass are positively correlated with survival  

---
 Skills Gained
- Data cleaning  
- Descriptive statistics  
- Exploratory data analysis  
- Data visualization using Matplotlib & Seaborn

---
