# diabetes-analysis
This repository contains a Python script for analyzing a diabetes dataset. The script performs data preprocessing, exploratory data analysis (EDA), feature engineering, and builds a classification model using RandomForestClassifier.

## Requirements

To run the script, you need to have the following packages installed:

- numpy
- pandas
- seaborn
- matplotlib
- missingno
- scikit-learn

You can install the required packages using pip:

```sh
pip install numpy pandas seaborn matplotlib missingno scikit-learn
```

## Dataset

The dataset used in this analysis is `diabetes.csv`. Ensure that the dataset is in the same directory as the script.

## Script Overview

The script performs the following steps:

1. **Data Loading and Initial Exploration**:
    - Loads the dataset using pandas.
    - Displays the first few rows and basic statistics.
    - Checks for missing values and data types.

2. **Data Preprocessing**:
    - Identifies categorical and numerical columns.
    - Handles missing values by replacing zeros with NaN and imputing with the median.
    - Detects and handles outliers using the IQR method.

3. **Exploratory Data Analysis (EDA)**:
    - Analyzes the distribution of categorical and numerical features.
    - Examines the relationship between features and the target variable.
    - Visualizes the correlation matrix.

4. **Feature Engineering**:
    - Creates new features based on existing ones (e.g., BMI categories, age groups).
    - Encodes categorical variables using label encoding and one-hot encoding.

5. **Model Building**:
    - Splits the data into training and testing sets.
    - Trains a RandomForestClassifier.
    - Evaluates the model using accuracy, precision, recall, F1 score, and AUC.

## How to Run

1. Clone the repository:

```sh
git clone https://github.com/yourusername/diabetes-analysis.git
```

2. Navigate to the repository directory:

```sh
cd diabetes-analysis
```

3. Ensure the dataset `diabetes.csv` is in the same directory.

4. Run the script:

```sh
python diabetes_analysis.py
```

## Results

The script prints the following evaluation metrics for the model:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC


## Acknowledgements

- The dataset used in this analysis is from [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).
- The script is inspired by common practices in data analysis and machine learning.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Contact

If you have any questions, feel free to contact me at [esraydin.2001@gmail.com].
