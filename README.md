# Titanic Data Exploration

Exploratory data analysis of the Titanic passenger dataset using Python, Pandas, NumPy, and Matplotlib.

## Dataset
891 passengers, 12 columns: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.

Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## Tools Used
- **Pandas** – loading, cleaning, and analyzing the data
- **NumPy** – numerical calculations
- **Matplotlib** – data visualization

## What I Did
- Loaded and inspected the dataset (`.head()`, `.shape`, `.info()`, `.describe()`)
- Checked and handled missing values (Age had 177 missing, Cabin had 687 missing)
- Grouped data to find survival rate by gender and passenger class
- Visualized findings with bar charts and a histogram
- Calculated mean and median age using both NumPy and Pandas

## Key Findings
- Overall survival rate: **38.4%**
- Female survival rate: **74.2%** vs Male survival rate: **18.9%**
- Survival by class: 1st class **63%**, 2nd class **47.3%**, 3rd class **24.2%**
- Mean age: **29.7**, Median age: **28.0**
- Most passengers were between 20-40 years old

## What I Learned
This was my first hands-on data exploration project. I practiced loading real-world data, handling missing values, using `groupby()` for aggregation, and building basic visualizations — foundational skills for machine learning work ahead.

## Files
- `Untitled0.ipynb` – the full notebook with code, outputs, and analysis
