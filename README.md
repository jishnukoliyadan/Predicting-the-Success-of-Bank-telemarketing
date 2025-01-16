# Predict the Success of Bank telemarketing

**MLP Project T32024** :: [Kaggle Competition](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing)

## Dataset

The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Files
- train.csv - the training set
- test.csv - the test set
- sample_submission.csv - a sample submission file in the correct format

**Input variables:**
1. last contact date: last contact date
2. age (numeric)
3. job : type of job
4. marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
5. education (categorical: "unknown","secondary","primary","tertiary")
6. default: has credit in default? (binary: "yes","no")
7. balance: average yearly balance, in euros (numeric)
8. housing: has housing loan? (binary: "yes","no")
9. loan: has personal loan? (binary: "yes","no")
10. contact: contact communication type (categorical: "unknown","telephone","cellular")
11. duration: last contact duration, in seconds (numeric)
12. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
14. previous: number of contacts performed before this campaign and for this client (numeric)
15. poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

**Output variable (desired target):**

16. target: has the client subscribed a term deposit? (binary: "yes","no")

## Evaluation

Submissions are evaluated on f1_score(average='macro') between the predicted classes and the True target.

## Only libraries allowed
1. NumPy
1. Pandas
1. Matplotlib
1. Scikit-learn 
1. XGBoost
1. Seaborn
1. Imblearn
1. SciPy
1. Pickle
1. regex
1. Lightgbm
1. Plotly

## Competition Result : TOP 2 percentile result

![](https://github.com/user-attachments/assets/bb56ef8f-38c8-4924-abee-9e70e1d223d4)
