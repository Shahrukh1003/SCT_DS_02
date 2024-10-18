# Titanic Dataset Exploratory Data Analysis (EDA)
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.


### Overview of the Notebook

1. **Introduction**
   - The notebook starts with a general task description. It involves performing data cleaning and exploratory data analysis (EDA) on a dataset, specifically the Titanic dataset from Kaggle.

2. **About the Dataset**
   - The Titanic dataset contains both numerical and string values. The columns include:
     - **Passenger ID**: Unique identifier for each passenger.
     - **Survived**: Binary value (1 or 0) indicating whether the passenger survived.
     - **Pclass**: Passenger class, representing socioeconomic status.
     - Other columns include information such as the passenger's name, age, gender, ticket fare, and whether they had any relatives aboard.

3. **Importing Libraries**
   - The necessary libraries for this analysis include:
     - `numpy` and `pandas` for data manipulation.
     - `matplotlib` and `seaborn` for data visualization.

4. **Reading the Dataset**
   - The Titanic dataset is loaded into a pandas DataFrame using the following code:
     ```python
     df = pd.read_csv("Titanic-Dataset.csv")
     df.head()
     ```
   - The first few rows of the dataset are displayed to give an overview of its structure.

5. **Shape of the DataFrame**
   - The shape of the DataFrame (number of rows and columns) is displayed to understand the size of the dataset.

6. **Data Cleaning & Preprocessing**
   - This section handles missing values, transforms data types, and prepares the dataset for analysis. Common tasks for the Titanic dataset include:
     - Filling or dropping missing data, particularly in columns like `Age`.
     - Converting categorical variables (e.g., `Sex`, `Embarked`) into numerical format.

7. **Exploratory Data Analysis (EDA)**
   - This section explores relationships between different features in the dataset. Examples of analyses include:
     - Survival rates across different passenger classes, genders, and age groups.
     - Visualizing data using histograms, bar charts, and box plots.
     - Creating correlation matrices to identify relationships between variables.
     - Investigating how factors like fare price, cabin location, and family presence affected survival rates.

8. **Visualizations**
   - The notebook includes several visualizations using `matplotlib` and `seaborn`, such as bar plots and heatmaps, to uncover patterns and trends in the data.

---

This notebook provides a comprehensive approach to exploring the Titanic dataset, from data cleaning to detailed visualizations, helping to uncover the factors that influenced survival rates aboard the Titanic.
