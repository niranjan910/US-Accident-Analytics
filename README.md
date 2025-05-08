
# US-Accident-Analytics

**Author:** Niranjan  
**Date:** 7 May 2025  

---
## Project Background

Road accidents are a leading cause of fatalities and economic losses worldwide, with the U.S. recording over 6 million crashes annually. Understanding accident patterns is critical for improving public safety, optimizing emergency response, and shaping infrastructure policies.

This project leverages a countrywide dataset of 1.5 million traffic accidents (2016–2023) to:
- Identify high-risk locations and times for accidents.
- Analyze contributing factors like weather, road conditions, and time of day.
- Predict accident severity to help authorities allocate resources efficiently.

---

## Data Structure & Initial Checks


| #  | Attribute                   | Description |
|----|-----------------------------|-------------|
| 1  | ID                          | This is a unique identifier of the accident record. |
| 2  | Severity                    | Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay). |
| 3  | Start_Time                  | Shows start time of the accident in local time zone. |
| 4  | End_Time                    | Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed. |
| 5  | Start_Lat                   | Shows latitude in GPS coordinate of the start point. |
| 6  | Start_Lng                   | Shows longitude in GPS coordinate of the start point. |
| 7  | End_Lat                     | Shows latitude in GPS coordinate of the end point. |
| 8  | End_Lng                     | Shows longitude in GPS coordinate of the end point. |
| 9  | Distance(mi)                | The length of the road extent affected by the accident. |
| 10 | Description                 | Shows natural language description of the accident. |
| 11 | Number                      | Shows the street number in address field. |
| 12 | Street                      | Shows the street name in address field. |
| 13 | Side                        | Shows the relative side of the street (Right/Left) in address field. |
| 14 | City                        | Shows the city in address field. |
| 15 | County                      | Shows the county in address field. |
| 16 | State                       | Shows the state in address field. |
| 17 | Zipcode                     | Shows the zipcode in address field. |
| 18 | Country                     | Shows the country in address field. |
| 19 | Timezone                    | Shows timezone based on the location of the accident (eastern, central, etc.). |
| 20 | Airport_Code                | Denotes an airport-based weather station which is the closest one to location of the accident. |
| 21 | Weather_Timestamp           | Shows the time-stamp of weather observation record (in local time). |
| 22 | Temperature(F)              | Shows the temperature (in Fahrenheit). |
| 23 | Wind_Chill(F)               | Shows the wind chill (in Fahrenheit). |
| 24 | Humidity(%)                 | Shows the humidity (in percentage). |
| 25 | Pressure(in)                | Shows the air pressure (in inches). |
| 26 | Visibility(mi)              | Shows visibility (in miles). |
| 27 | Wind_Direction              | Shows wind direction. |
| 28 | Wind_Speed(mph)             | Shows wind speed (in miles per hour). |
| 29 | Precipitation(in)           | Shows precipitation amount in inches, if there is any. |
| 30 | Weather_Condition           | Shows the weather condition (rain, snow, thunderstorm, fog, etc.) |
| 31 | Amenity                     | A POI annotation which indicates presence of amenity in a nearby location. |
| 32 | Bump                        | A POI annotation which indicates presence of speed bump or hump in a nearby location. |
| 33 | Crossing                    | A POI annotation which indicates presence of crossing in a nearby location. |
| 34 | Give_Way                    | A POI annotation which indicates presence of give_way in a nearby location. |
| 35 | Junction                    | A POI annotation which indicates presence of junction in a nearby location. |
| 36 | No_Exit                     | A POI annotation which indicates presence of no_exit in a nearby location. |
| 37 | Railway                     | A POI annotation which indicates presence of railway in a nearby location. |
| 38 | Roundabout                  | A POI annotation which indicates presence of roundabout in a nearby location. |
| 39 | Station                     | A POI annotation which indicates presence of station in a nearby location. |
| 40 | Stop                        | A POI annotation which indicates presence of stop in a nearby location. |
| 41 | Traffic_Calming             | A POI annotation which indicates presence of traffic_calming in a nearby location. |
| 42 | Traffic_Signal              | A POI annotation which indicates presence of traffic_signal in a nearby location. |
| 43 | Turning_Loop                | A POI annotation which indicates presence of turning_loop in a nearby location. |
| 44 | Sunrise_Sunset              | Shows the period of day (i.e. day or night) based on sunrise/sunset. |
| 45 | Civil_Twilight              | Shows the period of day (i.e. day or night) based on civil twilight. |
| 46 | Nautical_Twilight           | Shows the period of day (i.e. day or night) based on nautical twilight. |
| 47 | Astronomical_Twilight       | Shows the period of day (i.e. day or night) based on astronomical twilight. |

---
## Executive Summary

