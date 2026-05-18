🚢 Titanic Data Analysis - Exploratory Data Analysis (EDA) Project

📌 **Project Overview**
This repository contains a comprehensive Exploratory Data Analysis (EDA) and Statistical Testing framework designed to analyze the factors that influenced passenger survival during the historic Titanic disaster. Using the famous Titanic dataset, this project investigates how socio-economic status, gender, age, and family structures intersected to determine a passenger's fate.

The analytical workflow transitions seamlessly from raw data cleaning and profiling to rigorous multivariate validation, uncovering the underlying human and social patterns of the tragedy.

🔍 **Key Findings & Hidden Patterns**
During the deep-dive multivariate exploration, four critical insights were uncovered:

* **The Socio-Economic & Gender Priority:** The Titanic disaster wasn't just a matter of luck; it was a stark reflection of social privilege and chivalry. If you were a **Female** passenger who paid a **High Fare (1st/2nd Class)**, your chances of survival were exceptionally high (above 95%). Conversely, a solo male passenger in 3rd Class had the lowest survival probability.
* **The "Small Family" Sweet Spot:** Passengers traveling with small families (**1 to 3 members**) achieved the highest survival rates. 
* **The Large Family Penalty:** As family size grew to 4 or more, the survival rate dropped drastically. This indicates that larger families unfortunately lost crucial time trying to locate each other amidst the chaos on the sinking ship.
* **The Solitude Disadvantage:** Passengers traveling completely alone (Family Size: 0) faced a remarkably low survival rate (around 30%), highlighting how lack of immediate support affected outcomes during the evacuation.

🛠️ **Tech Stack & Libraries Used**
* **Language:** Python 3.x
* **Data Manipulation:** pandas, numpy
* **Data Visualization:** matplotlib, seaborn
* **Statistical Analysis:** scipy.stats (Chi-Square Testing, Data Imputation techniques)

📂 **Project Architecture & Methodology**
### 1. Data Profiling & Cleaning
* Checked dataset dimensions, structural types, and handled critical missing values (such as Age and Cabin).
* Addressed data integrity issues to ensure robust statistical comparisons.

### 2. Feature Engineering
* **Family Size:** Combined sibling/spouse (`SibSp`) and parent/child (`Parch`) attributes to calculate the exact family size for each passenger.
* **IsAlone:** Created a binary feature to isolate the behavioral patterns of solo travelers vs. families.

### 3. Key Analytical Insights
* **Class vs. Survival:** Statistically validated how the premium placement of 1st class cabins provided faster access to lifeboats.
* **Gender Dominance:** Analyzed the strict implementation of the "women and children first" protocol across different passenger decks.

📈 **Visualizations Included**
The notebook features highly interactive and clean plots following advanced layout styling rules:
* **Barplots & Countplots:** Displaying the direct correlation between survival rates, Gender, and Passenger Class (`Pclass`).
* **Distribution & KDE Plots:** Analyzing the age demographics of those who survived versus those who did not.
* **Heatmaps:** Highlighting correlations between structural numeric features like Fares and survival outcomes.

🚀 **How to Run this Project**
* **Clone the Repository:**
```bash
git clone [https://github.com/bishtmamta/Titanic-EDA.git](https://github.com/bishtmamta/Titanic-EDA.git)
cd Titanic-EDA
Install Dependencies:

Bash
pip install pandas numpy matplotlib seaborn scipy
Launch the Notebook:

Bash
jupyter notebook "titanic EDA project.ipynb"
🎯 Conclusion
The analysis mathematically proves that survival on the Titanic was highly systemic. Socio-economic boundaries and institutional guidelines (like class privileges and gender priority) created definitive life-or-death advantages. This project successfully transforms historical raw data into a clear sociological and statistical narrative.
