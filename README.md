# WeatherDashboard

# Requirements

[] 5 day forecast
[] rain radar
[] wind arrows
[] barometric lines
[] uv index
[] feels like temp
[] outside temp
[] air quality
[] rate of change of air pressure
[] weather alerts

# data sources

openweathermap api call

noaa weather radar

https://forecast.weather.gov/xml/current_obs/KMIA.rss

https://www.aviationweather.gov/api/data/dataserver?requestType=retrieve&dataSource=metars&stationString=KFLL&hoursBeforeNow=3&format=xml&mostRecent=true

https://www.ncei.noaa.gov/cdo-web/api/v2/stations

local weather station

NOAA Nearshore Wave Prediction System
https://polar.ncep.noaa.gov/nwps/images/rtimages/mfl/nwps/CG1/
https://polar.ncep.noaa.gov/nwps/nwpsloop.php?site=MFL&loop=wind&cg=1

https://ocean.weather.gov/Atl_tab.php#graphical

https://www.ndbc.noaa.gov/data/Forecasts/FZUS52.KMFL.html

# Messaging Protocol

MQTT

EspNOW
- Payload is limited to 250 bytes
- Encrypted and unencrypted unicast communication
- Up to 220 meters under ideal conditions
- Operating in the 2.4 GHz band
- No Message Acknowledgment

ZigBee

LoRa
