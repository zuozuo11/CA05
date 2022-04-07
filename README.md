# CA05


## Background
Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients
collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16
patient features. Note that none of the features include any Blood Test information.


---------------------------------------------------------------------------------------


## Install

import pandas as pd

import numpy as np

from sklearn.model_selection import train_test_split

from sklearn import linear_model

from sklearn.linear_model import LogisticRegression

from sklearn import metrics

import matplotlib.pyplot as plt

from sklearn.model_selection import GridSearchCV

from matplotlib import pyplot

from sklearn.metrics import confusion_matrix

from sklearn.metrics import classification_report

from sklearn.metrics import roc_curve, auc

import warnings


---------------------------------------------------------------------------------------
## Process

Data Source and Description

Build a binary classifier model

Display the Feature Importance of all the features sorted in the order of decreasing influence on the CVD Risk

Evaluate the performance of your model, explain the performance and draw a meaningful conclusion
