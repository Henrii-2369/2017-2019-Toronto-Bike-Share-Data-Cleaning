# 2017-2019-Toronto-Bike-Share-Data-Cleaning

The bike-share .csv files contain the following 9 fields in 2017 and 2018:

trip_id: unique identifier for each trip
trip_duration_seconds: duration of the trip measured in seconds
from_station_id: station ID where the trip started
trip_start_time: time when the trip started
from_station_name: name of the station where the trip started
trip_stop_time: time when the trip ended
to_station_id: station ID where the trip ended
to_station_name: name of the station where the trip ended
user_type: identify if the user has a membership or purchased a pass
The bike-share .csv files contain the following 11 fields in 2019 and 2020:

Trip Id: unique identifier for each trip (trip_id in 2017 and 2018 datasets)
Subscription Id: user membership/subscription id (not in 2017 and 2018 datasets)
Trip  Duration: duration of the trip measured in seconds (trip_duration_seconds in 2017 and 2018 datasets)
Start Station Id: station ID where the trip started (from_station_id in 2017 and 2018 datasets)
Start Time: time when the trip started (trip_start_time in 2017 and 2018 datasets)
Start Station Name: name of the station where the trip started (from_station_name in 2017 and 2018 datasets)
End Station Id: station ID where the trip ended (to_station_id in 2017 and 2018 datasets)
End Time: time when the trip ended (trip_stop_time in 2017 and 2018 datasets)
End Station Name: name of the station where the trip ended (to_station_name in 2017 and 2018 datasets)
Bike Id: unique identifier of each bicycle in circulation (not in 2017 and 2018 datasets)
User Type: identify if the user has a membership or purchased a pass (user_type in 2017 and 2018 datasets)
 

Station Information: Station data from the Bike Share API endpoint has been saved as a .csv (bikeshare_stations.csv).

Station Id	Station Name	latitude	longitude	Capacity
7000	Fort York  Blvd / Capreol Ct	43.639832	-79.395954	35
7001	Lower Jarvis St / The Esplanade	43.64783	-79.370698	15
7002	St. George St / Bloor St W	43.667333	-79.399429	19
...	...	...	...	...
 

Toronto Weather:  This is a dataset of historical weather in Toronto provided by the City of Toronto. The weather station is located at  43.63 latitudes and -79.4 longitude. All the file names contain the number 6158359, which is the TORONTO CITY CENTRE weather station ID. There is one .csv file for every month and these files have the following naming convention:

en_climate_hourly_ON_6158359_01-2017_P1H.csv
en_climate_hourly_ON_6158359_02-2017_P1H.csv
en_climate_hourly_ON_6158359_03-2017_P1H.csv
...
en_climate_hourly_ON_6158359_01-2018_P1H.csv
en_climate_hourly_ON_6158359_02-2018_P1H.csv
en_climate_hourly_ON_6158359_03-2018_P1H.csv
...
en_climate_hourly_ON_6158359_01-2019_P1H.csv
en_climate_hourly_ON_6158359_02-2019_P1H.csv
en_climate_hourly_ON_6158359_03-2019_P1H.csv
...
en_climate_hourly_ON_6158359_01-2020_P1H.csv
en_climate_hourly_ON_6158359_02-2020_P1H.csv
en_climate_hourly_ON_6158359_03-2020_P1H.csv
...
January = 01, February = 02, March = 03, April = 04, etc.

The weather .csv files contain the following 28 fields:

Longitude (x): Longitude co-ordinates for the climate station
Latitude (y): Latitude co-ordinates for the climate station
Station Name: The official name of the meteorological station
Climate ID: A 7 digit number assigned to the official weather observation site
Date/Time: Date and time of the measurement
Year: Year of the measurement
Month: Month of the measurement
Day: Day of the measurement
Time: Time of the measurement
Temp (°C): Temperature in degrees Celsius
Temp Flag: NA
Dew Point Temp (°C): Dew point temperature in degrees Celsius
Dew Point Temp Flag: NA
Rel Hum (%): Relative humidity as a percentage
Rel Hum Flag: NA
Wind Dir (10s deg): The direction from which the wind blows
Wind Dir Flag: NA
Wind Spd (km/h): The speed of motion of air in kilometres per hour
Wind Spd Flag: NA
Visibility (km): The distance at which objects of suitable size can be seen and identified
Visibility Flag: NA
Stn Press (kPa): The atmospheric pressure in kilopascals (kPa) at the station elevation
Stn Press Flag: NA
Hmdx: An index to indicate how hot or humid the weather feels to the average person
Hmdx Flag: NA
Wind Chill: An index to indicate how cold the weather feels to the average person
Wind Chill Flag: NA
Weather: Observations of atmospheric phenomenon including the occurrence of weather and obstructions to vision
