# :fish: SG Fishing Guide :fish:
##### An analysis of environmental factors affecting fish feeding behaviour to forecast future fishing conditions for a tiered pricing system of their fishing guide services

### Problem Statement
A fishing guide company called SG Fishing Guide operating in the Eastern waters of Singapore is exploring the feasibility of a tiered pricing system for their fishing guide services. Instead of having a fixed price for hiring a guide each day throughout the year, the company would like to have a tiered pricing system where customers will be charged:

 - lower prices for days when the fishing conditions are less than ideal, and 
 - higher prices for days with optimal fishing conditions. 

### Scope

This project aims to analyze the trends and patterns of environmental conditions which affect the quality of fishing and forecast the fishing conditions of future dates for the planning of their tiered pricing system.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|Station|string|changi|Location of measurement| 
|Year|integer|changi|Year of measurement| 
|Month|integer|changi|Month of measurement| 
|Day|integer|changi|Day of measurement| 
|Daily Rainfall Total (mm)|float|changi|Total rainfall in mm for the day| 
|Highest 30 min Rainfall (mm)|float|changi|Highest rainfall recorded in 30min intervals| 
|Highest 60 min Rainfall (mm)|float|changi|Highest rainfall recorded in 60min intervals| 
|Highest 120 min Rainfall (mm)|float|changi|Highest rainfall recorded in 120min intervals| 
|Mean Temperature (°C)|float|changi|Mean temperature in °C for the day| 
|Maximum Temperature (°C)|float|changi|Max temperature in °C for the day| 
|Minimum Temperature (°C)|float|changi|Min temperature in °C for the day| 
|Mean Wind Speed (km/h) |float|changi|Mean wind speed in km/h for the day| 
|Max Wind Speed (km/h)  |float|changi|Max wind speed in km/h for the day| 
|Region|string|combined_output|Region of measurement| 
|Station|string|combined_output|Location of measurement| 
|Date|string|combined_output|Date of measurement| 
|Daily_Rainfall_Total|string|combined_output|Total rainfall in mm for the day| 
|Highest Rainfall (mm) (30,60,120) min|string|combined_output|Highest rainfall recorded in 30, 60 and 120min intervals|
|Mean,Max,Min Temperature (°C)|string|combined_output|Mean, Max and Min temperature in °C for the day|
|Mean,Max Wind Speed (km/h)|string|combined_output|Mean and Max wind speed in km/h for the day|
|wbt_date|string|WetBulbTemperatureHourly|Date of measurement| 
|wbt_time|integer|WetBulbTemperatureHourly|Hour of the day of measurement| 
|wet_bulb_temperature|float|WetBulbTemperatureHourly|Hourly reading of Wet bulb temperature in °C| 
### Installation

*Clone the repository*

`gh repo clone qileaf/sg-fishing-guide`

or via html:

`https://github.com/qileaf/sg-fishing-guide.git`

*.ipynb*

The project file is in .ipynb format and was created in VS Code and Jupyter Notebook

*Dependencies*

Install the dependencies by opening your terminal in the project folder and run:

`pip install -r requirements.txt`

After installation, you should then be able to run the code smoothly! :smile:

