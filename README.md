# Bigfoot-Mid---Project-
COLUMN NAME    TYPE    DESCRIPTION
observed    string    Full text description of the sighting.
location_details   string   Details about the location of the sighting.
county    string    The county in which the sighting occurred.
state    string    The state in which the sighting occurred.
season    string    The season of the sighting.
title    string    The title of the sighting.
latitude    decimal    The latitude of the sighting.
longitude    decimal    The longitude of the sighting.
location    geopoint    The location of the sighting in WKT format.
date    date    The date of the sighting.
number    decimal    The report number.
classification    string    The report classification (Class A, Class B or Class C).
geohash    string    A geohash of the sighting location.
temperature_high    decimal    The high temperature the day of the sighting in degrees Fahrenheit.
temperature_mid    decimal    The midpoint between high and low temperatures the day of the sighting in degrees Fahrenheit.
temperature_low    decimal    The low temperature the day of the sighting in degrees Fahrenheit.
dew_point    decimal    The dew point the day of the sighting in Fahrenheit.  
humidity    decimal    The relative humidity the day of the sighting.    
cloud_cover    decimal    The cloud cover the day of the sighting as a percentage of the visible sky.
moon_phase    decimal    The fractional part of the lunar number - 0 is new moon, 0.5 is full moon.
precip_intensity    decimal    The precipitation intensity in inches per hour.
precip_probability    decimal     The probability of precipitation the day of the sighting.
precip_type    string    The type of precipitation the day of the sighting.
pressure    decimal     The pressure the day of the sighting.
summary    string    A human readable summary of the weather conditions the day of the sighting.
conditions    string     
uv_index    decimal    The UV index the day of the sighting.
visibility    decimal    The visibility the day of the sighting, in miles. Capped at 10.
wind_bearing    decimal    The direction the wind was coming from the day of the sighting.
wind_speed    decimal    The wind speed the day of the sighting in miles per hour.