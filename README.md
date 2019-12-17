# Data_Science_Fall_2019_Project

## GENERAL NOTES:

Many of the raw data CSV files are larger than GitHub's 100 mb maximum file size. As such, the 
raw data CSV files can be downloaded externally at the following URL:

[Raw Data URL](https://drive.google.com/drive/folders/1G-fV2YWhG_c2FKEsuA5vwFHj-6XhZKM6?usp=sharing)

The report that accompanies this project can be downloaded at the following URL:

[Final Report URL](https://docs.google.com/document/d/10fHlA0DAObA4DixgRPCk7LNVbzU070HJNloid45H1hA/edit?usp=sharing)

## Jupyter Notebooks

Two Jupyter notebooks were created and used in this project. They are titled `Data_Analysis.ipynb` and 
`Data_Processing.ipynb.` The first notebook is responsible for cleaning and merging the raw data. It generates
a CSV file titled `epa_noaa.csv` which is the final dataset. The second notebook is responsible for building
modeling the data via linear regression and visualizing the models. These notebooks can used in any Python 3 
environment with the following packages installed:

imutils
pandas
numpy
tqdm
matplotlib
seaborn
scikit-learn
scipy


## NOAA Daily Weather Data

### Description: 

Daily weather data for three cities (New York, Chicago, and Los Angeles) between Jan 1, 2015 and Dec 31, 2018.

[Data Source](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND)

### Metadata:

*All units are metric!*

[Metadata documentation source](https://www1.ncdc.noaa.gov/pub/data/cdo/documentation/GHCND_documentation.pdf)

* DATE: Date for which weather record is valid
* STATION: Station ID that corresponds to station that collected weather record
* PRCP: Daily Precipitation (millimeters)
* AWND: Average Daily Wind Speed (meters/second)
* SNWD: Daily Snow Depth (millimeters)
* SNOW: Daily Snowfall (millimeters)
* TMAX: Max Daily Temperature (Celsius)
* TMIN: Min Daily Temperature (Celsius)
* TAVG: Average Daily Temperature (Celsius)

## EPA AIR QUALITY

### Description:

Daily air quality data for three cities (New York, Chicago, and Los Angeles) between Jan 1, 2015 and Dec 31, 2018.

[Data Source](https://www.epa.gov/outdoor-air-quality-data/download-daily-data)

### Metadata:

*All units are metric!*

[Metadata documentation source](https://aqs.epa.gov/aqsweb/airdata/FileFormats.html)

* Date Local: Date for which air quality record is valid
* City Name: City for which air quality record is valid
* Event Type: Whether exceptional event (i.e. wildfire) occured during period in which data was collected
* 1st Max Value: Highest daily concentration recorded for given pollutant
* AQI: Air Quality Index for given pollutant
* Arithmetic Mean: Average daily concentration recorded for given pollutant

The pollutants included in the dataset (and their respective units of measurement) are provided below:
* CO: parts per million
* SO2: parts per billion
* Ozone: parts per million
* NO2: parts per billion