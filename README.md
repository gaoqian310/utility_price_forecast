<h2 align="center">Utility forecastor with historical data</h3>

<!-- ABOUT THE PROJECT -->
### About The Project

#### This project is sponsed by SPE Calgary Mentor Program

#### our goal is utilizing historical weather data, power generator data and elecricity price to forcast future electricity price

#### Date description for generation data
----------------
This historical generation data is from the same data source that is displayed on the Current Supply & Demand (CSD) report on the AESO's ETS website (see http://ets.aeso.ca/ets_web/ip/Market/Reports/CSDReportServlet). It contains data for the individual units on the CSD page.

The data is provided in both 5-minute and 1-hour intervals. The reported volume is the average generation over the given period. 

Please note that this data is not the same as settlement meter data. This data generally represents what was generated at the unit, not necessarily what is delivered to the AESO grid. In addition, the settlement meter data is of higher quality. However, this data may be the only available information for some assets.

The data is scheduled to be updated monthly.

DISCLAIMER
----------
The CSD data is provided on a best efforts basis and may contain errors. Please be aware that there is a significant amount of data in each file. It is possible that the 5-minute interval files may not completely load in Excel and will require a different method to view the data. Every effort will be made to ensure the 1-hour interval files can open in Excel.

If there are any questions or problems, please email the AESO at manalysis@aeso.ca.


COLUMN DEFINITIONS
------------------
Date (MST) - Hour start in Mountain Standard Time

Date (MPT) - Hour start in Mountain Prevailing Time (i.e. MST or MDT, as appropriate)

Asset Short Name - Abbreviation for asset

Asset Name - asset name

Asset Grouping - the meter that behind-the-fence assets share, if appropriate.

Volume - volume reported via SCADA (similar to that reported on CSD page)

Maximum Capability - maximum capacity reported to the AESO

System Capability - capacity available to AESO via contracted volume, if any

Fuel Type - main fuel categorization

Sub Fuel Type - sub fuel categorization

Planning Area - AESO planning area the asset is located in

Region - AESO region the asset is located in