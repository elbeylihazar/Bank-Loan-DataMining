# Bank-Loan-DataMining
## Project Overview 

This project focuses on developing a Bank Loan Predictor for the Dream Housing Finance company, which specializes in home loans. The goal is to automate the loan eligibility process based on customer information provided during the online application process. The company aims to streamline this process and specifically target customers who are eligible for loans.

The dataset used in this project contains various attributes such as Gender, Marital Status, Education, Income, Loan Amount, Credit History, and more, which are used to predict the loan approval.

## Technologies Used

KNIME: Utilized for data preprocessing and model training.
Naive Bayes: Employed as the primary algorithm for loan approval prediction.
K-Nearest Neighbor (KNN) and Cross-Validation methods were also tested.

## Project Structure

### 1-Data Extraction and Preprocessing:
The dataset was extracted from Kaggle.
Missing values were handled using rule-based filtering techniques.
Unnecessary data was removed for better prediction accuracy.
#### 2-Modeling:
Initial attempts included Cross-Validation and K-Nearest Neighbor (KNN) methods, but these resulted in low accuracy (around 68% and 61% respectively).
Naive Bayes algorithm provided the best accuracy of 80.83%.
#### 3-Prediction:
The model predicts loan approval based on a variety of customer factors.
The dataset is split into training and test sets for validation.
### 4-Results:
Best model accuracy: 80.83% using Naive Bayes.

## How to Use (with KNIME)
### 1-Clone the repository:
git clone https://github.com/<elbeylihazar>/Bank-Loan-DataMining.git
### 2-Open KNIME:
Download and install KNIME.
### 3-Load the project files into KNIME:
Open the workflow from the Bank-Loan-DataMining folder in KNIME.
### 4-Load the dataset:
In the workflow, load the dataset to the appropriate nodes for processing.
### 5-Run the data preprocessing steps:
Clean missing values and remove unnecessary columns by running the preprocessing steps in KNIME.

## Contribution

If you'd like to contribute, feel free to submit a pull request or provide suggestions for improvements.


## Next Steps

Improve the dataset with additional features to avoid overfitting.
Explore the potential of Decision Tree algorithms for better results.





 
