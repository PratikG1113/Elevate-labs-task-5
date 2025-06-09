# Elevate-labs-task-5

# 🧠 Task 5 - Exploratory Data Analysis (EDA)

## 📌 Objective
The goal of this task was to analyze the Titanic dataset using Exploratory Data Analysis techniques to uncover insights, patterns, and relationships using Python libraries.

---

## 📂 Dataset
- **Name**: Titanic Dataset  
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv)

---

## 🛠️ Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 🔍 Key Steps in EDA

### 1. Data Loading & Inspection
- Used `.head()`, `.info()`, `.describe()` to understand data structure and summary.

### 2. Data Cleaning
- Handled missing values (`Age`, `Embarked`)
- Dropped unnecessary columns (`Cabin`, `Ticket`)

### 3. Univariate Analysis
- Analyzed distribution of `Age`, `Fare`, and class counts using histograms and boxplots.

### 4. Bivariate Analysis
- Explored relationships between `Survived` and other variables like `Sex`, `Pclass`, and `Age`.

### 5. Correlation Analysis
- Created a heatmap and pairplot to visualize correlations between numerical features.

---

## 📈 Visualizations Included
- Histogram (Age, Fare)
- Boxplot (Age vs Survived)
- Countplot (Sex vs Survived, Pclass vs Survived)
- Heatmap (Correlation)
- Pairplot (Age, Fare, Pclass vs Survived)

---

## 🧠 Insights Gained
- Women had higher survival rates than men.
- First-class passengers were more likely to survive.
- Fare and Age had some correlation with survival.
- Strong correlation between Fare and Pclass.

Thanks to the Data Analyst Internship Program for this hands-on opportunity to apply EDA concepts on a real-world dataset.


