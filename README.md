# Script No.3 , COP6481,SP'24, Team 06

## GIS MAPPING for Credit Card Transactions

### Assignment

* Data preprocessing
* Geospacial Analysis
* Visualization
* Spacial Analysis
* Insights and Interpretation

### The Data Set

The dataset was generated in projects generate_data.py python file.
In total 2000 records were generated.
There were 500 unique merchants
There were 1800 unique persons

These are the columns for each transaction:

*Transaction ID*

Random Number

*Date*

Month of June 2023

*Amount*

Random number

*Latitude,Longitude*,

Generated by borough according to following ratios:

'Manhattan': 0.35,
'Brooklyn': 0.20,
'Queens': 0.20,
'Bronx': 0.15,
'Staten Island': 0.10,

*User ID,*

Random Number

*Status,*

Acceped or declined.
5% declined

*Merchant ID*

Random number

### Mapping Data

We used nyc_boroughs.geojson

This came from the NYC OpenData website at:
https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm

We performed the spacial joins with this data set and the generated data.

This our first visualization:

![CCTransactionMechantStatic.png](assets/CC Transaction Mechant Static.png?t=1709385626284)
