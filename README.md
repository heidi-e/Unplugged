# Unplugged
Predicting the projections of global greenhouse gas emissions from asset-level electricity generation

# Regression Models
This is my final group project for DS3000 that explores various machine learning models to make predictions in global greenhouse gas emissions from asset-level electricity generation.

# Installation
To run the jupyter notebook, you will need Python 3 and the following libraries:

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import scipy as sp
import seaborn as sns

from sklearn.preprocessing import StandardScaler, OneHotEncoder
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.svm import SVC
from sklearn.model_selection import ShuffleSplit
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score
from sklearn.compose import ColumnTransformer
from sklearn.ensemble import RandomForestRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.svm import SVR
from sklearn.metrics import mean_squared_error
import matplotlib as mpl
mpl.rcParams.update(mpl.rcParamsDefault)
```

# Usage
To start the notebook, simply download and open it through Jupyter Notebook. 
