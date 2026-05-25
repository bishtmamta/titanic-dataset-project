# 🚢 Titanic Survival Analysis – EDA Project

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the famous Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

The analysis explores how gender, passenger class, age, fare, and family size affected survival chances. The workflow includes data cleaning, feature engineering, visualization, and statistical insights to uncover hidden patterns in the dataset.

---

# 🔍 Key Findings

### 1. Gender had a strong impact on survival

Female passengers had significantly higher survival rates compared to males.

### 2. Passenger class influenced survival

1st class passengers were more likely to survive, while 3rd class passengers had the lowest survival rate.

### 3. Fare and survival were related

Passengers who paid higher fares generally had better survival chances.

### 4. Family size affected survival

Passengers traveling with small families had higher survival rates compared to solo travelers or very large families.

### 5. Children had better survival chances

The analysis suggests that children were given rescue priority during evacuation.

---

# 🛠️ Tech Stack & Libraries Used

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* scipy.stats

---

# 📂 Project Workflow

## 1. Data Understanding

* Dataset structure analysis
* Data types inspection
* Missing value identification

## 2. Data Cleaning

* Handling missing values
* Removing unnecessary columns
* Duplicate checking

## 3. Feature Engineering

Created new features such as:

### Family Size

\text{Family Size} = \text{SibSp} + \text{Parch}

### Is Alone

\text{Is Alone} = \begin{cases}1,&\text{Family Size}=0\0,&\text{otherwise}\end{cases}

---

# 📈 Visualizations Included

* Countplots
* Histograms
* KDE Plots
* Boxplots
* Heatmaps

These visualizations help analyze:

* Survival distribution
* Gender impact
* Passenger class trends
* Fare distribution
* Age distribution
* Correlation between numerical features

---

# 📊 Conclusion

The project demonstrates that survival during the Titanic disaster was strongly influenced by:

* Gender
* Passenger class
* Fare
* Age
* Family structure

The analysis highlights how social and economic factors played an important role in passenger survival outcomes.

