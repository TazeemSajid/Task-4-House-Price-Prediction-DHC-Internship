# Task-4-House-Price-Prediction-DHC-Internship
**Task 4: House Price Prediction**

**📌 Project Description**

In this task, i build a Linear Regression model to predict house prices using the Boston Housing Dataset.
The dataset contains information about housing in Boston, including crime rate, number of rooms, property tax, and more.
Our goal is to predict the median value of owner-occupied homes (MEDV).
📊 Steps Performed

**📂 Dataset**

I used the Boston Housing Dataset (CSV version).

Input Features (13):

CRIM – per capita crime rate by town

ZN – proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS – proportion of non-retail business acres per town

CHAS – Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX – nitric oxides concentration (parts per 10 million)

RM – average number of rooms per dwelling

AGE – proportion of owner-occupied units built prior to 1940

DIS – weighted distances to five Boston employment centres

RAD – index of accessibility to radial highways

TAX – full-value property-tax rate per $10,000

PTRATIO – pupil-teacher ratio by town

B – proportion of Black residents (special formula)

LSTAT – % lower status of the population

Output Target (1):

**⚙️ Steps Performed**

Load Dataset – Read the Boston Housing dataset (BostonHousing.csv)

Preprocessing

Normalized numerical features

Split into training (80%) and testing (20%) sets

Model Training – Trained a Linear Regression model

Model Evaluation – Calculated Root Mean Squared Error (RMSE) on test set

User Input Prediction – Allow user to enter custom input values (13 features) and predict the house price

**⚙️ Tools & Technologies**

Python 3

Pandas → Data handling

Scikit-learn → Train/test split, Random Forest, evaluation metrics

NumPy → Numerical operations

**▶️ How to Run**

Install dependencies:

pip install pandas scikit-learn numpy


Place the dataset and script in the same folder.

**Run the script:**

python task_3_house_price_pridiction.py
