# Titanic Dataset

The sinking of the Titanic is one of the most infamous shipwrecks in history. 

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

### Data

Titanic DataSet obtained from Kaggle: https://www.kaggle.com/c/titanic

### Goal

Build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).


#### 1. Titanic_Predictions_LogisticRegression_MRG - first predictions for Titanic performing EDA and prediction with Logistic Regression.
 * Accuracy ~= 75%

#### 2. Titanic_Predictions_RandomForests_MRG - second predictions for Titanic with additional feature engineering and prediction using an Random Forests model and gridsearch
 * Accuracy ~= 77%

#### 3. Titanic_Predictions_SVM_MRG - third preictions for Titanic with additional feature engineering and prediction using an SVM model and gridsearch
 * Accuracy ~= 79% (Top 20%)

#### 4. Titanic_Predictions_SVM_MRG - fourth preictions for Titanic with  prediction using an basic TensorFlow Neural Network.
 * Accuracy ~= 78%
