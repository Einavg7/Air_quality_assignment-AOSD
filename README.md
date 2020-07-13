# Air quality NO2 assignment - Analysis of Spatial-temporal Data 

In this project I used the national sensor data reported to and distributed by the European environmental agency of
the [European Air Quality Standards](https://ec.europa.eu/environment/air/quality/standards.htm).
Using point interpolation, I assessed whether the location of the Institute for Geoinformatics, Muenster (IFGI) 
during the year 2017 with respect to the European air quality standards of Nitorgen Dioxide (NO2) were met.

## Data

hourly time series: https://www.eea.europa.eu/data-and-maps/data/aqereporting-8  
(this may give you a file with URLs that need to be downloaded, separately or bulk.)

data on the air quality stations: http://ftp.eea.europa.eu/www/AirBase_v8/AirBase_v8_stations.zip  
(note that air quality stations have two types: station_type_of_area (e.g., “rural”, “urban”) and type_of_station (e.g. background, traffic); interpolating while ignoring this information may be meaningless)


