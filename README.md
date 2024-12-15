# Titanic Dataset: Exploratory Data Analysis (EDA)

## Overview
This project performs **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset.
 The goal is to analyze passenger information and uncover patterns or trends that influenced survival during the disaster.

## Dataset
The Titanic dataset used for this analysis includes information about:
- Passenger demographics (e.g., age, sex, class)
- Survival status
- Family relationships (siblings, spouses, parents, children)
- Ticket and cabin details

You can download the dataset from [Kaggle Titanic Dataset]

## Steps Performed
1. **Data Cleaning**
   - Handled missing values for columns like `Age`, `Cabin`, and `Embarked`.
   - Converted categorical variables into numerical form for analysis.
   - Dropped unnecessary columns such as `Name` and `Ticket` for simplicity.

2. **Exploratory Data Analysis (EDA)**
   - Explored relationships between variables using summary statistics and visualizations.
   - Analyzed survival rates based on:
     - Passenger class (`Pclass`)
     - Gender (`Sex`)
     - Age groups
     - Fare (`Fare`)
     - Embarkation point (`Embarked`)

3. **Visualizations**
   - Created bar plots, heatmaps, and histograms to understand data distribution and relationships.
   - Visualized survival trends using **seaborn** and **matplotlib**.

## Installation and Usage
### Prerequisites
Ensure Python is installed on your system. The recommended Python version is 3.8 or later.

 Install Required Packages
pip install -r requirements.txt

Results
Key Findings:
Women had a significantly higher survival rate than men.
Passengers in First Class were more likely to survive compared to those in lower classes.
Younger passengers had better chances of survival.

Visual Insights:
Heatmaps revealed correlations between features such as Fare and Pclass.
Survival was strongly influenced by gender and passenger class.

File Structure

│
├── data/
│   ├── train.csv           # Titanic training dataset
│   ├── test.csv            # Titanic test dataset (optional)
│
├── titanic_eda.ipynb       # Jupyter Notebook with analysis and visualizations
├── requirements.txt        # List of required Python packages
├── README.md               # Project description and instructions


Acknowledgments
Dataset provided by Kaggle Titanic Competition.
Inspired by Titanic Data Science Solutions on Kaggle.



