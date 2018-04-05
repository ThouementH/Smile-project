# Smile-project
Code related to the Smile project
This part of the smile project aims at analysing water quality data in nearly real time.
Water quality data can be studied as independant variate, the test employed to validate the data or create alarms are then univariate tests.
A major issue of the study of outflow of wasterwater treatment plant is that rain events differ greatly from dry weather events but do not require to set an alarm - rain is normal functionning. To prevent alarms to go off, we look at several variables at once, in a multivariate analysis.

Several steps are necessary:
- cleaning the data to work with reliable data sets.
- understanding the data
- test forecasting models, i.e. ARIMA model
- test correlations with PCA, moving-window PCA, adaptable-window size PCA
- ultimate goal: take into consideration the uncertaincy in a complex PCA that takes also the uncertainty of the data into consideration. 
