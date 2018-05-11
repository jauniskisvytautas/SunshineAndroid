# SunshineAndroid
# Description
Android application that gets fake weather data from api.

# Entity
Attributes:
COLUMN_DATE: date in string format
COLUMN_MIN_TEMP: minimal expected temperature
COLUMN_MAX_TEMP: maximum expected temperature
COLUMN_HUMIDITY: humidity in %
COLUMN_PRESSURE: pressure in hPa
COLUMN_WIND_SPEED: wind speed in km/H

```
 for (int i = 0; i < jsonWeatherArray.length(); i++) {

            long dateTimeMillis;
            double pressure;
            int humidity;
            double windSpeed;
            double windDirection;

            double high;
            double low;

            int weatherId;

```
# Fake Data source
"https://andfun-weather.udacity.com/weather"
Returns json with real-time fake weather data


# UI
UI Final
![screenshot_20180329-102453_sunshine](https://user-images.githubusercontent.com/34191652/38078426-ee5821b8-3344-11e8-96b7-f8d6beb39fe7.jpg)
![screenshot_20180329-102459_sunshine](https://user-images.githubusercontent.com/34191652/38078423-ee08ed46-3344-11e8-9d63-5f61c49ce7b7.jpg)
![screenshot_20180329-102518_android system](https://user-images.githubusercontent.com/34191652/38078424-ee21f6c4-3344-11e8-92a8-d7ed66338112.jpg)
![screenshot_20180329-102526_sunshine](https://user-images.githubusercontent.com/34191652/38078425-ee3b82a6-3344-11e8-8b08-6ca06b1b208c.jpg)
