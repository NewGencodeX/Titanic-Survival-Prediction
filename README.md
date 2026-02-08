# Titanic-Survival-Prediction
End-to-end data science project using the Titanic dataset: data cleaning, EDA, feature engineering, and machine learning.

## Dataset Overview
- PassengerId → Unique ID

- Survived → Target variable (0 = No, 1 = Yes)

- Pclass → Passenger class (1st, 2nd, 3rd)

- Sex → Male or Female

- Age → Passenger age

- SibSp → Number of siblings/spouses onboard

- Parch → Number of parents/children onboard

- Fare → Ticket fare

- Embarked → Port of embarkation

## Size and Structure of Data
The dataset contains information on 891 passengers with 3 identifiers, 4 numerical features and 5 categorical features.

## Exploratory Data Analysis

### Overall Survival Distribution
![Bar chart showing Titanic passenger survival rates: 562 passengers did not survive and 345 survived, representing approximately 38% overall survival rate](outputs/figures/survival_distribution.png)

📌 Insight: More passengers did not survive → dataset is imbalanced.

### Survival by Gender
![Grouped bar chart comparing Titanic survival rates by gender. Female passengers: 81 did not survive, 233 survived. Male passengers: 468 did not survive, 109 survived. Females had significantly higher survival rates than males](outputs/figures/survival_by_gender.png)

📌 Insight: Females had a much higher survival rate than males.

### Survival by Passenger Class
![Grouped bar chart showing Titanic survival outcomes by passenger class. First class: 80 deaths, 136 survivors (63% survival rate). Second class: 97 deaths, 87 survivors (47% survival rate). Third class: 372 deaths, 119 survivors (24% survival rate). Demonstrates inverse correlation between passenger class and mortality](outputs/figures/survival_by_class.png)

📌 Insight: First-class passengers survived significantly more than third-class.

### Age Distribution by Survival
![Visualization comparing age distribution between Titanic passengers who survived and those who did not](outputs/figures/survival_by_age.png)

📌 Insight: Survivors skew slightly younger, but age is less dominant than gender or class.