README.md

This project utilizes Principal Component Analysis (PCA) and logistic regression to analyze the breast cancer dataset from scikit-learn. The goal is to identify essential variables that can be leveraged to secure donor funding for cancer research, with a focus on the Anderson Cancer Center.

Files
`cancer_analysis.py`: Python script containing the code for the analysis.
`README.md`: This file, providing a description of the project and instructions.
Requirements
Python 3.6 or higher
scikit-learn
pandas
matplotlib
Installation

Install the required libraries using pip:
pip install scikit-learn pandas matplotlib
Running the Analysis
Execute the Script:
python cancer_analysis.py
Output

The script will generate:
A scatter plot visualizing the data projected onto the first two principal components.
The accuracy and a classification report of the logistic regression model.
The explained variance ratio of the principal components.
Analysis Steps
Data Loading: Loads the breast cancer dataset from scikit-learn.
Preprocessing: Scales the features using `StandardScaler`.
Dimensionality Reduction: Applies PCA to reduce the data to two principal components.
Visualization: Creates a scatter plot of the principal components.
Model Training: Splits data into training and testing sets, then trains a logistic regression model.
Model Evaluation: Evaluates the model on the testing set, prints accuracy and classification report.
Variance Analysis: Prints the explained variance ratio of the principal components.
Interpretation

This analysis helps identify the most significant variables in the breast cancer dataset. These variables can be used to inform targeted donor funding initiatives, potentially leading to more effective research and treatment strategies.
