## Topic -- LoanDelinquency
Home Credit Group is an international consumer finance provider with operations in 10 countries. It focuses on responsible lending primarily to people with little or no credit history. 
Since the business model of Home Credit Group mainly focuses on unbanked population, it has no way to determine if a person is likely to repay the loan since it’s traditionally done using a metric like Credit Score etc. 

Our project intends to use their data and predicts using statistics and machine learning how likely a potential borrower is to repay back the loan and identify potential defrauders.

## Team
Nirbhay Kekre<br>
Rajat Chaurasia<br>
Yash Kumar Mahajan

## Data
Name: Home Credit Default Risk <br>
Link: https://www.kaggle.com/c/home-credit-default-risk/data <br>
Size: 688MB <br>
  Train Data - 308k * 122 <br>
  Test Data - 48.7k * 121


## Preprequisites 
1. Anaconda Jupyter should be installed.<br>
2. Install LightGBM Model from Anaconda or run the following command.<br> 
 conda install -c conda-forge lightgbm 


## How to run
1. Clone the repository <br>
2. Download and unzip the dataset using the link above and place it under the data/ directory.
3. Create a directory called preprocessedData/
4. run preprocessing.ipynb
5. run RandomForest.ipynb, LogisticRegression.ipynb, LightGradientBoostingMachine.ipynb

## ROC-AUC:
Baseline: 0.628 <br>
Random Forest: 0.744 <br>
Logistic Regression: 0.755 <br>
LightGBM: 0.763
