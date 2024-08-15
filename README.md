# Tennis - Pre-Processing & Machine Learning

![Project Image](https://images.pexels.com/photos/209977/pexels-photo-209977.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## 🚀 Introduction

This project focuses on data pre-processing related to tennis and the application of various machine learning models to analyze these data.

## 🛠️ Technos Used

- **Python**
- **Pandas**
- **Scikit-Learn**
- **Matplotlib / Seaborn**

## 🔑 Project Workflow

1. **Import CSV Files**
- CSV containing the ATP matches year by year : Folder To-Import-Model
- CSV containing the information about all the ATP Players : atp_players.csv
- Excel file containing the names of the 500 best tennis players today : Top500-Modified.xlsx

2. **Data Processing**
- Keep only the most significant columns.
- Data Format : Date.
- Data Quality : Avoid to have 2 values for the same thing.
- Replace the Null values with a real value.

3. **Prepare the Dataframe for Supervised Learning**
- Transform the dataframe to have a column 'Player1' and a columns 'Player2' with their main characteristics.
- Export it into CSV.

4. **Supervised Learning**
- Import the CSV File created during the Pre-Processing step.
- Classification Model : RandomForestClassifier
- Fit this model on the training data.
- Check the performance.
