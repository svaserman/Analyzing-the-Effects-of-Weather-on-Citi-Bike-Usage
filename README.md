# Exploring the Effects of Weather on Citi Bike Usage

#### Project Description:
While Citi Bikes have become and an increasingly more popular and efficient mode of transportation, weather can certainly play a role in determining whether or not an individual would want to travel via bicycle. For this reason, my project aims to examine Citi Bike users and analyze the effects of weather on Citi Bike usage. 
#### Objectives: 
- Develop a deeper understanding of Citi Bike Customers
    - Age
    - Sex
    - User Type (Annual subscriber or have 24-hour/ 3-day pass)
    - Trip Duration
- Determine whether there is a correlation between weather and Citi Bike usage
    - Daily Average Temperature
    - Daily Snow Fall / Depth
    - Daily Rain Fall

# Data:

#### Citi Bike Trip History Source: https://ride.citibikenyc.com/system-data
- Citi Bike offers Trip History data which includes Trip Duration, Start and Stop Time, Start and Stop Date, Start and Stop Locations, Station ID, Bike ID, Station Longitudes and Latitudes, User Type, Gender, and Year of Birth.

#### Climate Data Online Search: https://www.ncdc.noaa.gov/cdo-web/search
- This site allows users to view past weather data based on date range and location. For this particular project, I will be using a weather station located in Central Park, NY, NY which will include daily records of High and Low Temperatures, Precipitation, Snow Fall, Snow Depth, Wind Speed, and Fog.

## CitiBike Dataset Variables
- Trip Duration (seconds)
- Start Time and Date
- Stop Time and Date
- Start Station Name
- End Station Name
- Station ID
- Station Lat/Long
- Bike ID
- User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
- Gender (Zero=unknown; 1=male; 2=female)
- Year of Birth


## Weather info (all taken from USW00094728	station in NY CITY CENTRAL PARK, NY US)
- WSF2 - Fastest 2-minute wind speed
- WSF5 - Fastest 5-second wind speed
- SNOW - Snowfall
- WT03 - Thunder
- WT04 - Ice pellets, sleet, snow pellets, or small hail"
- PRCP - Precipitation
- WT05 - Hail (may include small hail)
- WT06 - Glaze or rime
- WT08 - Smoke or haze
- SNWD - Snow depth
- WDF2 - Direction of fastest 2-minute wind
- AWND - Average wind speed
- WDF5 - Direction of fastest 5-second wind
- PGTM - Peak gust time
- WT01 - Fog, ice fog, or freezing fog (may include heavy fog)
- TMAX - Maximum temperature
- WT02 - Heavy fog or heaving freezing fog (not always distinguished from fog)
- TAVG - Average Temperature.
- TMIN - Minimum temperature
- TSUN - Total sunshine for the period
