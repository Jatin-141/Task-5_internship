# Task 5 – Exploratory Data Analysis (EDA)

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA)
on the Titanic dataset to identify patterns, relationships, and key factors
influencing passenger survival.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)

---

## Dataset

The Titanic dataset contains information about 891 passengers,
including demographic details, ticket class, fare, and survival status.

Key Features:

- survived (Target variable)
- pclass (Passenger class)
- sex
- age
- fare
- sibsp (Siblings/Spouses aboard)
- parch (Parents/Children aboard)
- embarked
- and others

---

## Data Cleaning Performed

- Filled missing values in `age` using median.
- Dropped `deck` column due to excessive missing values.
- Filled missing values in `embarked` and `embark_town` using mode.
- Verified dataset integrity after cleaning.

---

## Exploratory Analysis Conducted

### 1. Survival Distribution
Analyzed overall survival rate of passengers.

### 2. Gender vs Survival
Identified significant survival differences between males and females.

### 3. Passenger Class vs Survival
Analyzed impact of socioeconomic status on survival probability.

### 4. Combined Analysis (Gender + Class)
Identified most vulnerable and most protected groups.

### 5. Age vs Survival
Examined age distribution and average age differences.

### 6. Fare vs Survival
Analyzed relationship between ticket price and survival.

### 7. Correlation Analysis
Used heatmap to identify relationships between numeric variables.

---

## Key Findings

1. Gender was the strongest predictor of survival.
2. Female passengers had significantly higher survival rates than males.
3. Passenger class strongly influenced survival probability.
4. Higher ticket fare was associated with higher survival rates.
5. Age showed moderate influence but was weaker than gender and class.
6. Third-class males were the most vulnerable group.
7. First-class females had the highest survival probability.

---

## Conclusion

The EDA reveals that survival on the Titanic was heavily influenced by
gender and socioeconomic status. Evacuation policies and structural
inequalities significantly impacted survival outcomes.

This analysis demonstrates the ability to:

- Perform structured data exploration
- Interpret statistical results
- Use visualizations for insight generation
- Communicate analytical findings effectively

---

## Deliverables Included

- `titanic_eda.ipynb` (Jupyter Notebook)
- `eda_report.pdf` (Exported report)
- README.md
