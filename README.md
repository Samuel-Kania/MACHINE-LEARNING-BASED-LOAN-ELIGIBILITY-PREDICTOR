LOAN ELIGIBILITY PREDICTION USING DECISION TREE

- Project Overview

This project builds a Decision Tree Machine Learning model to predict loan eligibility based on applicant information. The notebook performs data preprocessing, model training, feature importance analysis, model evaluation, and visualization of the decision tree.

The goal is to demonstrate how a Decision Tree Classifier can be used to analyze applicant characteristics and determine whether a loan should be approved.


 -Objectives

* Load and explore the loan dataset
* Handle missing values and preprocess the data
* Encode categorical variables
* Train a Decision Tree classification model
* Identify the most important features influencing loan approval
* Evaluate model performance
* Visualize and interpret the decision tree
* Allow users to test predictions with new input data


- Dataset
 dataset link: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

The model uses a loan applicant dataset (`train.csv`) which contains information about applicants such as:

* Gender
* Marital Status
* Education
* Applicant Income
* Loan Amount
* Credit History
* Property Area
* Loan Status (target variable)

The dataset is uploaded manually in the notebook.


-Technologies and Libraries

This project is implemented in Python using the following libraries:

* Pandas – Data manipulation and analysis
* NumPy – Numerical computations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* Scikit-learn – Machine learning algorithms and model evaluation

-Key machine learning tools used include:

* Decision Tree Classifier
* Label Encoding
* Train-Test Split
* Feature Importance Analysis


-Project Workflow

1. Import Libraries

The project begins by importing the required Python libraries for data analysis, visualization, and machine learning.

 2. Load the Dataset

The training dataset (`train.csv`) is uploaded and loaded into a Pandas DataFrame.

3. Data Preprocessing

* Check for missing values
* Handle missing data using forward and backward filling
* Encode categorical variables using Label Encoding

 4. Train-Test Split

The dataset is split into training (80%) and testing (20%) sets to evaluate model performance.

 5. Model Training

A Decision Tree Classifier is trained using the training data to predict loan eligibility.

6. Feature Importance Analysis

The model identifies which features contribute most to the prediction of loan approval.

7. Simplified Model

A smaller decision tree is trained using the top three most important features to improve interpretability.

 8. Model Evaluation

The model predicts outcomes on the test dataset and calculates accuracy to measure performance.

 9. Decision Tree Visualization

The trained decision tree is visualized to show how decisions are made based on feature values.

 10. Decision Rules

The tree structure is exported as readable decision rules, making the model easier to interpret.

 11. Interactive Prediction

The notebook includes a simple input prompt interface where users can enter new applicant details and get a loan eligibility prediction.


- Outputs

The project produces the following outputs:

* Model accuracy score
* Feature importance ranking
* Decision tree visualization
* Human-readable decision rules
* Loan eligibility prediction for new applicants



- How to Run the Project

1. Install required libraries

bash
pip install pandas numpy matplotlib seaborn scikit-learn


2. Open the notebook:


'DT_model.ipynb'


3. Upload the train.csv dataset when prompted.

4. Run all cells to train the model and generate predictions.



-Conclusion

This project demonstrates how Decision Tree models can be used for classification problems such as loan approval prediction. By analyzing applicant features and identifying the most influential factors, the model helps illustrate how machine learning can support **data-driven decision-making in financial services**.

