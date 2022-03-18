# The Underlying relations of Traditional Taxi Services And Competitive Shared-Riding Services: Understanding The Senario Where Shared-Riding Services Succeed And Providing Recommendations For Traditional Services Stakeholders

## 1. Introduction.
As the technology briskly took a step forward over the decade, the life quality of citizens has been
drastically improved. It has been addressed by several resources[2, 3] that the traditional taxi and
high volume for-hire vehicle(FHV) services1 industry has been heavily affected and even overtaken by
giant shared-riding transportation services known as High Volume For-Hire Vehicle(HVFHV)2, such
as Uber and Lyft since 2017 [9]. Based on monthly data provided by Taxi and Limousine Commission
of New York(TLC)[1], the research aims to understand the underlying relations between Traditional
Taxis and HVFHV by examine the scenarios where HVFHV dominates Taxi services. HVFHV services
and traditional services are still closely related and HVFHV perform better possibly mainly rely on
the utilization of internet technology. This is concluded from the finding that the number of pickups
of HVFHV forms a good linear relationship with Yellow Taxi’s data on a daily basis. As a result,
traditional taxi services would still have chances to win back the market by applying information
technologies to their business and boost their services like HVFHV services do.

- Full Report Link: https://www.overleaf.com/read/qwcptssmfnvg

### MAST30034 Project 1 - Quantitative Analysis
- Student Name: ChenghaoLi
- Student ID: 1067999
- Due Date: Friday 16th of August, 2021 11:59:00 am (AEST).


### Dependencies
- Language: Python 3.9
- Packages / Libraries: pandas, pyspark, sklearn, statsmodels, folium, os, bokeh, geopandas, numpy, seaborn, matplotlib.pyplot, statsmodels

### Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- NYC Traffic Data: https://data.cityofnewyork.us/Transportation/Traffic-Volume-Counts-2014-2019-/ertz-hr4r
- NYC Extreme Weather: https://www.weather.gov/okx/stormevents


### Directory
- `raw_data`: Contains all the raw data files. External Can be download through "DownloadData.ipynb" and "ExternalData.ipynb" notebook.
- `preprocessed_data`: Contains all the preprocessed data files. Run notebook "Preprocessing.ipynb" should generate and save all needed preprocessed data.
- `plots`: Output and saved plots.
- `code`: 
    - "DownloadData.ipynb" for "Downloading Data" and "Installing Packages".
    - "ExternalData.ipynb" for "Accesing and Downloading, Preprocessing External Data".
    - "Preprocessing.ipynb" for "Data preprocessing, feature engineering and saving to local".
    - "GeoMap.ipynb" for "Data Visualization within Geolocational map".
    - "OverAllAnalysis.ipynb" for "Data Aggregation and Visualisation on a Daily or Weekly Basis".
    - "Correlation.ipynb" for "Finding initial underlying linear relations between attributes".
    - "LinearModel.ipynb" for "Statistical Modelling".

### Other

- Big thanks to https://github.com/akiratwang/
- How to install and use PySpark? https://github.com/akiratwang/MAST30034_Python/blob/main/advanced_tutorials/
