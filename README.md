# Classification-of-interacting-patterns
## Model for predicting interacting residues

Classifying interacting and not-interacting patterns. Each pattern contain 17 amino acids (fixed length pattern). Interacting patterns are shown by label 1 and non-interacting pattern by label 0.

## Usage
**To install packages (imbalanced-learn, pandas, scipy, numpy, scikit-learn, sklearn )**

pip3 install -r requirements.txt

**To run python code**

python code.py

## Data Preprocessing
* Features and Labels splitting
* Under-sampling the data to improve Data imbalance
* Splitting data into train and validation dataset

## Feature Extraction
* Integer Encoding
* Binary Profiling
* Molecular_weight

## The following models were built
* Random Forest Classifier
* Random Forest Regressor
* Support Vector Machine (SVM)
* K Nearest Neighbors (KNN)
* Logistic Regression

## Result
**Random Forest Regressor** comes out to be the best among all the above models.

**Accuracy score:** 0.66312 (on 70% dataset), 0.64313 (on 30% dataset)

(It was a competition on Kaggle, 70% data is used for public leaderboard and 30% data for private leaderboard.) 
