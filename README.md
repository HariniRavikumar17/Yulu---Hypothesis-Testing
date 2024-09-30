# Yulu - Hypothesis Testing

# About Yulu
  Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting. Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient! Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

# Business Problem
# The company wants to know:

1] Which variables are significant in predicting the demand for shared electric cycles in the Indian market?

2] How well those variables describe the electric cycle demands

# Column Profiling:

1] datetime: datetime

2] season: season (1: spring, 2: summer, 3: fall, 4: winter)

3] holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)

4] workingday: if day is neither weekend nor holiday is 1, otherwise is 0.

5] weather:
   
   a: Clear, Few clouds, partly cloudy, partly cloudy
   
   b: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
   
   c: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
   
   d: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

6] temp: temperature in Celsius

7] atemp: feeling temperature in Celsius

8] humidity: humidity

9] windspeed: wind speed

10] casual: count of casual users

11] registered: count of registered users

12] count: count of total rental bikes including both casual and registered

# Concepts Used:

1] Bi-Variate Analysis

2] 2-sample t-test: testing for difference across populations

3] ANNOVA

4] Chi-square
