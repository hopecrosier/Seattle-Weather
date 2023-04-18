# Seattle-Weather Introduction
Repository to hold files and information related to the Seattle Weather Project in DATA 3320, which aims to compare rainfall in Seattle and St. Louis. Initial conclusion was that St. Louis gets more rain inches wise while Seattle gets more days where it rains overall. 

## Requirements
Software used in this project consists of Google Colab for data preperation and analysis, and excel for the storing of data sets. 

## Data
Source for Seattle and St. Louis rain data comes from the National Centers for Environmental Information linked below:
  https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
 and then were downloaded from the professor's github linked below:
 https://github.com/brian-fischer/DATA-3320/tree/main/weather
 
 ## Data Preperation
 To prepare data, we took the two previously mentioned data sets, replaced null values, filtered columnns of interest, renamed values and combined all the data into one clean data set. The file that holds the notebook for the cleaning of this data is in the Notebooks folder in the file "Data_Preparation.ipynb", and the clean data frame that was created from this notebook is in the Weather folder in the file "clean_seattle_stl_weather.csv"

## Data Analysis
To analyze the data gathered from the data preperation step of this project, I made new dataframes looking at only specific observations based on amount of rain, graphs depicting average rainfall from multiple time frames, and outliers in the data. These ways of looking at the code allowed me to come to a conclusion regarding the overarching question we have been aiming to answer in this project. The code executed to get these visualizations and conclusions can be found under the "Data_Analysis.ipynb" file in the Notebooks folder.

## Author
Hope Crosier is the author of this repository. She is a undergraduate computer science student at Seattle University, and her linked in here: https://www.linkedin.com/in/hope-crosier/

## License
This repository and all corresponding code components are liscenced under the MIT License
