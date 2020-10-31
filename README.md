# Time-Series-Analysis

# PROJECT TITLE 1:			Climate Change:  Earth Surface Temperature Data.

PROBLEM STATEMENT:	An attempt to study land surface data through time series analysis.

DATA:	This data was put together by Berkeley Earth, which is affiliated with Lawrence Berkeley National Laboratory.  Clean and non-processed data.  The data can be found @:    https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data.  Here it is saved in the global.txt file.
      
PROGRAMMING LANGUAGE:	Python.

LIBRARIES USED:	Numpy, Pandas, Matplotlib, PmdArima, Statsmodel.psa.seasonal, Statsmodel.psa.api, Holt, AdFuller, etc.

MODEL (Comparison Metrics = RMSE)
Model	RMSE
Holt’s Winter exponential smoothing.	1.8253
S-ARIMA	1.9866

BEST MODEL:	Holt’s Winter Exponential Smoothing.



# PROJECT TITLE 2:			U.S. Air Traffic Statistics (Jan 2000 – Feb 2020).

PROBLEM STATEMENT:	An attempt to study U.S. Air Traffic data through time series analysis.

DATA:	This data was gleaned from the United States Bureau of Transportation Statistics.  The link to the data can be found here.  The data can be found @:  https://www.transtats.bts.gov/TRAFFIC/

PROGRAMMING LANGUAGE:	Python.

LIBRARIES USED:	Numpy, Pandas, Matplotlib, PmdArima, Statsmodel.psa.seasonal, Statsmodel.psa.api, Holt, AdFuller, etc.

MODEL (Comparison Metrics = RMSE)
Model	RMSE
Holt’s Winter exponential smoothing.	6043058.18
S-ARIMA	1716615.61

BEST MODEL:	S-ARIMA.

