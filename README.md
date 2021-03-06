# COVID-19-Dashboard

This Dahboard replicates and extends the COVID-19 Dashboard by JHU and makes it available in free of charge Software Power BI Desktop.

Note, that publishing it to the web is not free. For more Information please visit the official Power BI website.

Please check the Terms of Use before reusing it.

![Image of Yaktocat](https://github.com/EED85/COVID-19-Dashboard/blob/master/files/Screenshot%20COVID-19%20Dashboard.png)



## Data Source

This repo loads the following csv files from https://github.com/CSSEGISandData/COVID-19 from the web-data branch

- cases.csv
- cases_country.csv
- cases_time.csv

## Features

### implemented

- Additional slicer
    - Continent Slicer
    - relative Date Slicer
- Imporved interactions
- Drill Down to a Data Table for a Country_Region
- Additional Measures
    - Moving Average of Confirmed
    - Moving Average of Confirmed Rate
    - Death Rate
    - Confirmed Doubling Time

### Ideas

- Compare COVID-19 Spread between countries
- Additional Measueres
    - ....
- Bookmarks
- Quickinfos
- ...

## Manual

### Set up Power Bi Desktop

- Install the latest Power BI Desktop Version on your Windows PC
- Clone this Repository and open the Power Bi Template "COVID-19.pbit"
- When openening, the Report will refresh automatically to get latest Data
    - you might be asked for authorisation, please choose anonymous
- Save the Dashboard in the top directory of this repository
It loads the Data via Power BI Service and sets up an customized Dashboard in Power BI.

### Refresh the Data

#### Power Bi Desktop

- Just open the pbix file and refresh the data

#### Power BI Service

You need a Power Bi License in order to pubish this report
in Power BI Service

- Publish the Power Bi Desktop File to a workspace
- Configure the AUthorisation
- Configure the Refresh Schedule 

## Documentation

You find further documentation in the corresponding folder [documentation](https://github.com/EED85/COVID-19-Dashboard/blob/master/documentation/measures.md)

### Measures

Please check 
[measures.md](https://github.com/EED85/COVID-19-Dashboard/blob/master/documentation/measures.md)

## Terms of Use

Please visit https://github.com/CSSEGISandData/COVID-19 and check the terms of use

## Other Dashboards

[COVID-19 Dashboard by JHU](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)


[Robert Koch-Institut: COVID-19-Dashboard](https://experience.arcgis.com/experience/478220a4c454480e823b17327b2bf1d4/page/page_1/)


