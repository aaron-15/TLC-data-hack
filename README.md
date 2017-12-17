## The TLC data challenge in the Kaggle competition asks to create a predictive model to analyze trip duration. I have used this dataset  to create value in methods different than a predictive model. In the notebooks I have performed spatial and temporal clustering to understand the behavioral patterns of users which can be leveraged by different types of industries.


### Notebook - 'Exploratory Analysis of Variables'
Inital Exploratory Analysis of the TLC entire dataset done in this notebook

### Notebook - 'Hourly pattern Spatial clustering'
This notebook analyses the spatial and temporal patterns in taxi dataset like weekly, monthly, hourly pickups and dropoffs The Manhattan census tracts are clustered according to these pattern variables.

###  Notebook - 'Hotspots_Coldspots_Analysis'
According to Tobler's first law of geography - "everything is related to everything else, but near things are more related than distant things."

The taxi pickups, dropoffs, trip durations values within a census tract are related to its neighbouring census tracts. This spatial autocorrelation is studied in this notebook. This is a part of Exploratory Spatial Data Analysis (ESDA). I have used these methods to find the hot spots and cold spots in Manhattan for the different variables

###  Notebook - 'Regression'
Literature review of the taxi-dataset analysis shows that taxi data has been used in prediction of unment demand. (NYU-CUSP Capstone) https://medium.com/@NYCTLC/students-use-tlc-data-to-study-unmet-taxi-demand-and-find-ideal-spots-for-taxi-relief-stands-644e40ebe11a

The taxi dataset is used to predict the taxi trip duration from the taxi data. The notebook shows an implementation of a predictive model.

Credits: Vishwajeet Shelar for this contribution towards this analysis