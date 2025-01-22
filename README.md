# Exploring Voter Turnout Modeling

This project analyzes voter registration and history data from Alamance County, North Carolina, to build a predictive model for voter turnout during the 2020 general election.

## Purpose
The goal is to:
1. Understand patterns in voter registration and turnout.
2. Build a logistic regression model to predict voter participation based on available features.

## How to Review the Code
1. **Data Preparation**:
   - Loads voter registration and history datasets.
   - Filters data to include only Alamance County voters.
   - Provides an overview of dataset size and structure.

2. **Modeling and Analysis**:
   - Splits the data into training and testing sets.
   - Uses logistic regression to predict voter turnout.
   - Evaluates the model with metrics like accuracy and ROC-AUC.

3. **Visualization**:
   - Uses `matplotlib` and `seaborn` for data exploration and insights.

## Data Files
- `VR_Snapshot_20201103_Alamance.csv`: Voter registration snapshot for Alamance County.
- `ncvhis1.txt`: Voter history data.

## Requirements
To run this project, install the following packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage
1. Clone the repository and ensure the required data files are in the project directory.
2. Run the Jupyter Notebook or Python script to process data and train the model.
3. Review model outputs and visualizations to draw conclusions about voter turnout patterns.
