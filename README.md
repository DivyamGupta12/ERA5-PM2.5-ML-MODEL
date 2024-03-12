# ERA5-PM2.5-ML-MODEL
This repository contains the project files for the selection task of the IP0NB000016 project. 

The predictors data is taken from - https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels-monthly-means?tab=overview
It contains the variables - Dewpoint Temperature, U component of wind, V component of wind, Surface Pressure, Temperature and Total precipitation having values depending on the latitude, longitude and time
The time range is from 2007 to 2022
The latitude and longitude range are from 8 to 37 and 68 to 97, corresponding to Indias lat-lon range 

Another dataset with same lat-lon range and variables with time range 2023 - 2024 is also used for prediction of future values, the same dataset is included in the repository

The target data has been taken from - https://sites.wustl.edu/acag/datasets/surface-pm2-5/#V5.GL.04
It contains the percentage of population which is lie in a specific PM 2.5 concentration range, for different states from 1998 to 2022
This data file is included in the repository

the 21500685_Divyam_IP0NB0000016_selectiontask.ipynb contains the required code

Libraries used - 
Pandas
,Numpy
, Matplotlib
, Basemap
, Xarray
, Netcdf
, Sklearn
, XGBoost
and Cartopy
References - 
Articles and papers from www.sciencedirect.com  
  NetCDF Primer - https://ornl-training.github.io/python-advanced-pandas/01-data-formats/
  Getting Hands on Climate Data - https://nordicesmhub.github.io/climate-data-tutorial/
