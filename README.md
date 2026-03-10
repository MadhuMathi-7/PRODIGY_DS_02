📌 Task-02: Data Cleaning and Exploratory Data Analysis

This project focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic Dataset provided by Kaggle.

The objective is to understand the dataset, clean missing or inconsistent data, and explore relationships between variables to identify patterns and trends.

📂 Dataset

The dataset used in this project contains passenger information from the Titanic ship, including:

PassengerId

Pclass (Passenger Class)

Name

Sex

Age

SibSp

Parch

Ticket

Fare

Cabin

Embarked

Survived (Target Variable)

🧹 Data Cleaning Steps

The following preprocessing steps were performed:

Checked dataset structure using info() and describe()

Identified missing values

Filled missing values in:

Age using mean

Embarked using mode

Handled missing Cabin values

Verified data consistency

📊 Exploratory Data Analysis (EDA)

Several visualizations were created to analyze patterns in the dataset:

Survival count distribution

Survival rate by gender

Passenger class distribution

Passenger class vs survival

Age distribution of passengers

Correlation heatmap between numerical variables

🔎 Key Insights

Some important patterns observed:

Female passengers had a higher survival rate than males.

Passengers in 1st class had a higher survival probability compared to 3rd class.

Younger passengers showed slightly higher survival chances.

Higher fare passengers tended to have better survival rates.

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
