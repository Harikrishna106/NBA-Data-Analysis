# NBA-Data-Analysis

This Jupyter Notebook (`nba analysis.ipynb`) provides a practical demonstration of **data analysis techniques** focused on **NBA player statistics**.
It covers **data loading**, **cleaning**, and **visualization** to gain insights into player data.

## 🔍 Key Analysis & Visualization Steps

This notebook illustrates the following essential stages of data analysis:

### 📥 Data Loading
- Reads NBA player statistics from a CSV file (`nba.csv`) into a Pandas DataFrame.

### 🧾 Data Inspection
- Uses `.info()` and `.describe()` to summarize data types, non-null counts, and basic statistics.
- Checks for missing values using:
  ```python
  df.isnull().sum()
  df.isnull().mean()

🧹 Missing Value Handling
Drops columns with over 40% missing values.

### Fills:

Numerical columns with mean.
Categorical columns with "unknown".

### 📊 Visualization: Player Distribution
Uses seaborn.countplot to display player frequency, ordered by appearance count.
### 🛠️ Setup and Dependencies
To run the notebook, make sure you have Python and the following libraries installed:

pip install pandas 
numpy matplotlib seaborn

### 🎯 Objective
This notebook is a simple and effective example of:

Initial data exploration
Data cleaning
Basic visualization

This notebook demonstrates efficient data preprocessing and visualization techniques on an NBA dataset.
