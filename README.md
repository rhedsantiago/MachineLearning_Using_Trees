README
# MachineLearning_Using_Trees
Using a mpg dataset, we use Machine Learning using trees to extract information from the dataset.

Simply download the cmp-assignment-2.py file and run it on google colab

Imports Used
import pandas as pd
import numpy as np
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.model_selection import GridSearchCV
import graphviz
from sklearn import tree
import statsmodels.api as sm
from sklearn.metrics import mean_squared_error
import matplotlib.pyplot as plt
from sklearn.ensemble import RandomForestRegressor
from sklearn.ensemble import AdaBoostRegressor
from sklearn.tree import export_graphviz
from xgboost import XGBRegressor
from xgboost import plot_tree
import matplotlib.pyplot as plt