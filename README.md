# Seattle-Weather Introduction
Repository to hold files and information related to the Seattle Weather Project in DATA 3320, which aims to compare rainfall in Seattle and St. Louis

## Data
Source for Seattle and St. Louis rain data comes from the National Centers for Environmental Information linked below:
  https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
 and then were downloaded from the professor's github linked below:
 https://github.com/brian-fischer/DATA-3320/tree/main/weather
 
 ## Data Preperation
 To prepare data, we took the two previously mentioned data sets, replaced null values, filtered columnns of interest, renamed values and combined all the data into one clean data set. The file that holds the notebook for the cleaning of this data is in the Data Preperation folder in the file "Data_Preparation.ipynb", and the clean data frame that was created from this notebook is in the Weather folder in the file "clean_seattle_stl_weather.csv"
