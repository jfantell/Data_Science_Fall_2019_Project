# Data_Science_Fall_2019_Project

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