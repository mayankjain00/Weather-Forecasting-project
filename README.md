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












System Requirement:
** Python 3.6
BeautifulSoup
Pandas
Numpy
Matplotlib
Seaborn
Openpyxl
Sklearn
wxPython
**









User Guide:

** Step 1: Download & Install Python 3.6
Step 2: Go to Terminal & Download Python Library (py -3.6 –m pip install ____)
Step 3: Go to ‘Weather_Prediction’ folder & click data set and download
Step 4: The forecast result will be stored in ‘prediction’ folder. The prediction statistics will be stored in ‘statistics’ folder

**







Developer Tools:

** Programming Language: Python
IDE: PyCharm
GUI: wxPython, wxFormBuilder
Web Scraping: BeautifulSoup, ParseHub
Debugging & Testing: Jupyter Notebook
Data Format: Microsoft Excel
