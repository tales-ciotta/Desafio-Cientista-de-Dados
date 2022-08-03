
# Comparison of Salary Prediction models + EDA

Prediction of Adult income based on Census Data using machine learning classification methods.


## Goal
The goal of this project is to predict if the yearly wage of an individual exceeds 50k or is equal or less than 50k using different machine learning classification models to compare the results.
## Data Description
The data was extracted from a Census Bureau database and consists of a list of features of a person and his income per year.

A brief description of the features:

#### **Predictors:**
- age: continuous.
- workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- fnlwgt: continuous.
- education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
- education_num: continuous.
- marital_status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
- occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
- relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- sex: Female, Male.
- capital_gain: continuous.
- capital_loss: continuous.
- hours_per_week: continuous.
- native_country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
#### **Target:**
- yearly_wage: >50K, <=50K
## Models Compared
The machine learning classification models compared in this project were:
- Logistic Regression
- Random Forest
- Decision Tree
- Gradient Boosting
- K-Nearest Neighbors 
## Requirements
This project requires **Python 3.9** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## How to Run
1. Open the notebook file with Jupyter Notebook or any editor of your preference
2. Run the cells
3. Make sure the dataset, test and train files are in the same folder as your notebook file
## Conclusions
The model that had the best performance was Gradient Boosting