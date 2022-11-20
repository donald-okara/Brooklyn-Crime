###  Project Description

The Brooklyn-Crime project is a data science whose purpose is crime forecast. This project was inspired by the rising rates of crime back home.


## The phases were: 
### 1) Data Mining
After scouring the internet for open Nairobi data, I moved on to a city probably just as riddled with crime. New York. Specifically Brooklyn. Sources for my data were:

Complaints: [NYPD Complaint Map (Year to Date) | NYC Open Data (cityofnewyork.us)](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Map-Year-to-Date-/2fra-mtpn)
Precincts: [Police Precincts | NYC Open Data (cityofnewyork.us)](https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz)

Zillow(Real estate data):[New York State Real Estate Dataset | Kaggle](https://www.kaggle.com/datasets/polartech/new-york-state-real-estate-dataset)

Census:[Census Demographics at the Neighborhood Tabulation Area (NTA) level | NYC Open Data (cityofnewyork.us)](https://data.cityofnewyork.us/City-Government/Census-Demographics-at-the-Neighborhood-Tabulation/rnsn-acs2)

Precincts: [Police Precincts | NYC Open Data (cityofnewyork.us)](https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz)

### 2) Data Exploration & Data Cleaning
#### a) Data Cleaning
I filtered missing data for relevant columns in an SQL query for Census, Complaints and precincts. 
I converted datatypes for longitude and latitude into float for Complaints and precincts.
I geocoded Census and Zillow and added pecinct data to all geodataframes.

#### b) Data Exploration
Graphs and maps were plotted for all relevant data. 

### 3) Feature Engineering
*In progress or yet to be updated.......*

### 4) Predictive Modeling
*In progress or yet to be updated.......*

### 5) Visualization & Presentation
*In progress or yet to be updated.......*

To run you need a competent IDE that supports python (VS code will suffice) and python installed in your device with all relevant packages.

#### Credit
##### Data
City of New York: [NYC Open Data - (cityofnewyork.us)](https://opendata.cityofnewyork.us/) & Kaggle learning community: Kaggle.com/learn
