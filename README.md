# COVID-19-Dashboard

This Dahboard replicates and extends the COVID-19 Dashboard by JHU and makes it available in Power BI Desktop 

Please check the Terms of Use before reusing it.

## Data Source

This repo loads the following csv files from https://github.com/CSSEGISandData/COVID-19 from the web-data branch

- cases.csv
- cases_country.csv
- cases_time.csv

## Features

### implemented

- Continent Slicer
- Imporved interactions

### Ideas

- Compare COVID-19 Spread between countries
- Additional Measueres
    - Death Rate
    - Infection Rate
    - Confirmed Moving Average
    - ...
- Drill through for Country Region
- Time Slicer
- Bookmarks
- Quickinfos
- ...

## Manual

### Set up Power Bi Desktop

- Install the latest Power BI Desktop Version on your Windows PC
- Clone this Repository and open the Power Bi Template "COVID-19.pbit"
- Refresh the Report to get latest Data (Home Ribbon)
    - you will be asked for authorisation, please choose anonymous
It loads the Data via Power BI Service and sets up an customized Dashboard in Power BI.

### Refresh the Data

#### Power Bi Desktop

- Just open the pbix file and refresh the data

#### Power BI Service

- Publish the Power Bi Desktop File to a workspace
- Configure the AUthorisation
- Configure the Refresh Schedule 


## Terms of Use

Please visit https://github.com/CSSEGISandData/COVID-19 and check the terms of use

## Other Dashboards

[COVID-19 Dashboard by JHU](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)


[Robert Koch-Institut: COVID-19-Dashboard](https://experience.arcgis.com/experience/478220a4c454480e823b17327b2bf1d4/page/page_1/)


