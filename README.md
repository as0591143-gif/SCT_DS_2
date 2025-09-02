# SCT_DS_2
Project Title
Exploratory Data Analysis on Titanic Dataset
Description
This task is about initial exploration and assessment of the classic Titanic dataset. The goal is to understand its structure, check data types, and identify missing values before further analysis or modeling.
Dataset
Dataset: Titanic (typically "train.csv")
Variables include: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.
Steps Performed
Loaded Titanic dataset using pandas.
Displayed first few rows using data.head() for a preview.
Checked data types and null values:
Used data.info() to examine column types and non-null counts.
Used data.isnull().sum() to count missing values per column.
Findings
Most columns have complete data; however, 'Age', 'Cabin', and 'Embarked' contain missing values.
'Cabin' has a significant amount of missing data.
Categorical fields like 'Sex', 'Embarked', 'Cabin', and 'Name' will require encoding or special attention for future modeling.
Next Steps
Impute or handle missing values.
Encode categorical variables for modeling.
Visualize data distributions and relationships (histograms, bar charts, etc.).
Prepare data for predictive modeling.
How to Run
Open the notebook in Jupyter/Colab.
Run all cells sequentially.
Review printed data overviews and missing value summary.
Tools Used
Python 3.x
Pandas
Jupyter Notebook
