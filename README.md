# Name of Project

ML_CA04_Ensemble Model


# Project Overview

The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. The following is a description of our dataset:
• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
• Number of attributes (Columns): 7
• Number of instances (Rows): 48,842


# Please download two data files first

1. Census dataset: https://drive.google.com/file/d/1rsQXXHqxeM8bB002RN30oXGBljbNBjow/view?usp=sharing


# Open colab:
https://colab.research.google.com/drive/1MLmiohNvjuAbQ4i8-YL--fx4yslwRECJ?usp=sharing

# Import packages list below:

```bash
#Import packages
import pandas as pd
import numpy as np

#Import viz packages
import matplotlib.pyplot as plt

#Import decision tree packages
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier
from sklearn.ensemble import GradientBoostingClassifier
from xgboost import XGBClassifier

from sklearn.preprocessing import LabelEncoder

from sklearn.metrics import classification_report, confusion_matrix
from sklearn.metrics import roc_curve
from sklearn.metrics import auc
from sklearn.metrics import roc_auc_score
from sklearn.metrics import accuracy_score
from sklearn.metrics import precision_score
from sklearn.metrics import f1_score
from sklearn.metrics import recall_score
```


# Installation

- Mounted the google drive to make files readable: drive.mount('/content/drive/')
- Enjoy the code

# Attention
Please see the answer of Q3 in word doc

# Contact info

Name: Mandy He
Email: she3@lion.lmu.edu
