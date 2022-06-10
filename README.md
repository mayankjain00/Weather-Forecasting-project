Weather Forecasting
Weather-Forecast-And-Prediction

#------Aim-------#

To provide a dataset with recommendations based on the personalized Weather preduct.
import pandas as pd # data processing, CSV file I/O
import numpy as np # linear algebra
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
import seaborn as sns

# ----datetime objects---- #
#from datetime import datetime, timedelta

#dataset
data=pd.read_csv("GlobalLandTemperaturesByMajorCity.csv")
data

#top 5 record to fatch
data.head()

#all infromation in data
data.info()
