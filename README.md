# BA_ML_CUP

This script performs data pre-processing, feature engineering, and prediction of a classification task on customer data. The customer data is split into several .csv files, which are read and combined into a single dataframe. The required libraries are installed and imported, including numpy, pandas, matplotlib, seaborn, tqdm, and scikit-learn.

## Environment Settings
The script starts by mounting a Google Drive and creating a dataset directory to store the data files. It then copies the required data files from Google Drive to the dataset directory.

## Data Preparation
The script reads in the .csv data files using pandas and combines them into a single dataframe. The net value of each sale is re-calculated and the final dataframe is created by merging information from multiple .csv files.

## Data Pre-processing
The data is pre-processed by filling in missing values and encoding categorical variables. Additionally, the data is split into training and testing sets.

## Feature Engineering
The script performs feature engineering by calculating new variables based on the existing ones, such as the ratio of order net value to the total number of items in the order.

## Model Training and Evaluation
The script trains an XGBoost classifier on the pre-processed and engineered data and evaluates its performance using accuracy, confusion matrix, and classification report.

## Usage
To run the script, make sure to change the WORKING_DIR variable to the correct path for the data files. Additionally, you may need to install the required libraries if they are not already present.
