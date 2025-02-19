# data_preprocessing_tools
Overview

This project demonstrates data preprocessing techniques using Python and the Scikit-Learn library. It covers handling missing data, encoding categorical data, splitting datasets into training and test sets, and feature scaling.

Prerequisites

Ensure you have the following dependencies installed:

Python 3.x

NumPy

Matplotlib

Pandas

Scikit-Learn

You can install the required packages using:

pip install numpy matplotlib pandas scikit-learn

Dataset

The dataset (Data.csv) should contain multiple columns, including:

Categorical and numerical features

A dependent variable column

Code Breakdown

1. Import Libraries

numpy, matplotlib.pyplot, and pandas for data handling and visualization.

sklearn.model_selection.train_test_split for splitting the dataset.

sklearn.preprocessing for encoding and scaling.

2. Load Dataset

Reads Data.csv into a Pandas DataFrame.

Splits data into independent variables (X) and the dependent variable (y).

3. Handling Missing Data

Uses SimpleImputer to replace missing values with the mean of the respective column.

4. Encoding Categorical Data

Uses OneHotEncoder to encode categorical independent variables.

Uses LabelEncoder to encode categorical dependent variables.

5. Splitting Data

Splits the dataset into a training set (80%) and test set (20%).

6. Feature Scaling

Uses StandardScaler to normalize numerical features.

Running the Code

Ensure Data.csv is in the working directory.

Run the script:

python script.py

The script will print the processed datasets and transformations applied.

Expected Output

Preprocessed Data Matrix (X)

Encoded Categorical Variables

Splitted Training and Test Data

Scaled Feature Matrix

Notes

Ensure the dataset is clean before running the script.

The random_state=1 ensures reproducibility in the train-test split.

Feature scaling is necessary for optimal performance in ML models.
