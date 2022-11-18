# Machine-Learning---sklearn
Machine Learning on google Colab - Boston Housing and Titanic

Boston Housing
- Descriptive Analysis
- Linear Regression Model
- Prediction
- Stochastic Gradient Descent (SGD) - Ridge Regression
- Stochastic Gradient Descent (SGD) - Elastic Net Penalty
- KFold and Cross Validation Scores

Source:
data_url = "http://lib.stat.cmu.edu/datasets/boston"

Package Use:
from sklearn.preprocessing import scale
from sklearn.model_selection import train_test_split
from sklearn.linear_model import SGDRegressor
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import KFold
from sklearn.model_selection import cross_val_score
-------------------

Titanic
- Exploratory Data Analysis
- Data Cleansing
- Transformation - Sex and Embarked Columnes
- Build a logistic regression model
- Prediction 
- KFold and Cross Validation Scores

Package Use:
from sklearn.preprocessing import scale
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import KFold
from sklearn.model_selection import cross_val_score
