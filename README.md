# DengAI_Capstone_Project

## Libraries used:

import pandas as pd
import numpy as np
import seaborn as sns

from pandas.plotting import scatter_matrix
from pandas import DataFrame
from pandas import concat
from pandas import read_csv
from pandas import datetime

from matplotlib import pyplot as plt

from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import mean_absolute_error,make_scorer
from sklearn.model_selection import GridSearchCV
from sklearn.cross_validation import ShuffleSplit
from sklearn.model_selection import train_test_split

from sklearn.ensemble import RandomForestRegressor
fromfrom  sklearn.treesklearn  import DecisionTreeRegressor
from sklearn.ensemble import AdaBoostRegressor

from keras.models import Sequential
from keras.layers import Dense
from keras.layers import LSTM
from keras.layers import Dropout
from keras.layers import Activation
from keras.callbacks import ModelCheckpoint
from keras.regularizers import L1L2
from keras.layers import Embedding
from keras.layers import Conv1D, GlobalAveragePooling1D, MaxPooling1D
