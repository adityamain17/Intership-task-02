🚢 Titanic Dataset - Exploratory Data Analysis (EDA)
📌 Overview

This project explores the famous Titanic dataset, a classic dataset used in data science and machine learning. The goal of this analysis is to understand the data, identify patterns, and uncover insights about the factors that influenced passenger survival during the Titanic disaster.

📂 Dataset

The dataset contains information about passengers on the Titanic, including:

Survived (0 = No, 1 = Yes)

Pclass (Passenger class: 1st, 2nd, 3rd)

Sex

Age

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Fare (Ticket price)

Embarked (Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton)

🛠️ Steps in EDA

Data Cleaning

Handling missing values (Age, Embarked, Cabin).

Converting datatypes where necessary.

Removing duplicates.

Univariate Analysis

Age distribution.

Passenger class distribution.

Gender distribution.

Fare distribution.

Bivariate/Multivariate Analysis

Survival rate by gender.

Survival rate by class.

Survival rate by age groups.

Survival rate by embarkation port.

Survival relation with fare.

Combined analysis: Gender + Class.

Visualization

Histograms, count plots, boxplots, violin plots.

Heatmap of correlations.

📊 Key Insights

Overall survival rate was about 38%.

Women and children had much higher survival chances than men.

First-class passengers had better survival rates compared to second- and third-class passengers.

Higher fare was positively correlated with survival.

Passengers from Cherbourg had higher survival rates compared to Southampton and Queenstown.

📌 Tools Used

Python

pandas for data manipulation

seaborn & matplotlib for visualization

numpy for numerical operations

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/titanic-eda.git


Install required libraries:

pip install pandas seaborn matplotlib numpy


Run the Jupyter Notebook / Python script to explore the dataset and see visualizations.

📌 Conclusion

The analysis highlights how gender, class, and age played a major role in survival during the Titanic disaster. Socio-economic factors and the “women and children first” policy greatly influenced survival chances.
