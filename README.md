📊 Dataset Collection README

This folder contains three datasets used for Machine Learning classification tasks.
Each dataset has been cleaned and is ready to use for training predictive models.


🍷 Wine Quality Dataset

Source: UCI Machine Learning Repository / Kaggle
File: winequality-red.csv

Objective: Predict wine quality (Good vs. Bad) using chemical properties.

Features:

Fixed acidity, Volatile acidity, Citric acid

Residual sugar, Chlorides, Free sulfur dioxide

Total sulfur dioxide, Density, pH, Sulphates, Alcohol

Target:

Quality (integer score 0–10).

Converted into binary classification:

Good (≥7) → 1

Bad (<7) → 0.

💡 Useful for practicing Gradient Boosting, Random Forests, Logistic Regression.


🍄 Mushroom Classification Dataset

Source: UCI Mushroom Dataset / Kaggle
File: mushrooms.csv

Objective: Predict if a mushroom is Edible or Poisonous.

Features:

Cap shape, Cap surface, Cap color

Odor, Gill size, Gill color

Stalk shape, Stalk color, Ring type, Habitat, etc.

Target:

Class (e = edible, p = poisonous).

💡 Great dataset for XGBoost, Decision Trees, Feature Importance visualization.
⚠️ Note: Accuracy often reaches 100% because the features perfectly separate classes.



🏥 Healthcare Loan Dataset

Source: Provided dataset (credit_train.csv)
File: credit_train.csv

Objective: Predict whether a loan will be fully paid or charged off.

Features:

Current Loan Amount, Term, Credit Score, Annual Income

Years in current job, Home Ownership, Purpose of loan

Monthly Debt, Years of Credit History, Credit Problems

Bankruptcies, Tax Liens, etc.

Target:

Loan Status:

Fully Paid → 1

Charged Off → 0.

💡 Realistic dataset for imbalanced classification, XGBoost / Gradient Boosting, and Cross-validation experiments.



🚀 Usage

All datasets are suitable for classification tasks.

Apply preprocessing:

Handle missing values

Encode categorical variables (e.g., One-Hot Encoding)

Normalize if needed

Evaluate using:

Accuracy, ROC-AUC, Confusion Matrix, Feature Importance



✨ With these datasets, you can practice end-to-end ML workflows:
Data Cleaning → Feature Engineering → Model Training → Model Evaluation → Interpretation
