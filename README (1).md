
# **End-To-End Deployment of Flight Price predictions Using Heroku**
 The main agenda of this project is:

1. Perform extensive Exploratory Data Analysis(EDA) on the Airline Dataset.

2. Build an appropriate Machine Learning Model that will help various Airline to predict their respective Price based on certain features

3. Deploy the Machine learning model via Heroku that can be used to make live predictions of Flight Price.

## Installation

To install the libraries used in this project. Follow the 
below steps:

```bash
!pip install cufflinks
!pip install chart_studio
!pip install pandas-profiling

from chart_studio.plotly import plot,iplot
from sklearn.ensemble import ExtraTreesRegressor
from sklearn.model_selection import train_test_split
from sklearn.ensemble import  ExtraTreesRegressor
from sklearn.ensemble import RandomForestRegressor
from sklearn.model_selection import RandomizedSearchCV
from sklearn.metrics import mean_absolute_error,mean_squared_error
from catboost import CatBoostRegressor
from lightgbm import LGBMRegressor


import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import xgboost as xgb
import cufflinks as cf
import seaborn as sns
import pickle 


%matplotlib inline
```
    
## Running Flask Api

To run tests, run the following command

```bash
  python app.py
```
## 🛠 Skills
1. Data Scientist
2. Data Analyst
3. Business Analyst
4. Machine Learning 

