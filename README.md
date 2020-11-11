Python Modules:
--------------
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import seaborn as sns
from matplotlib import pyplot as plt
from matplotlib import rcParams

import missingno as msno
# ggplot import *
#import ggplot
import matplotlib.pyplot as plt
%matplotlib inline

from sklearn.preprocessing import LabelEncoder
import lightgbm as lgb
from tqdm import tqdm
from subprocess import check_output
from time import gmtime, strftime
import gc
from sklearn.model_selection import (train_test_split, GridSearchCV)
from sklearn.metrics import (roc_curve, auc, accuracy_score)
from subprocess import check_output
---------------------------------------------------------------------
R Modules:
---------
library(reshape)
library(reshape2)
library(xgboost)
library(caret)
library(jsonlite)
library(dplyr)
library(Matrix)
library(doParallel)
library(lubridate)