# 2024-YHM-Weather
I have set up a bunch of Python scripts for both visualizations and to take the info from a database to show monthly highs, lows, precipitation among plenty of other metrics.

This script is ready to run entirely for Canadian cities if you use the same website to download from the database, so minimal changes will be needed for the same outputs. 
The website of interest is here: https://hamilton.weatherstats.ca/download.html.
Go to Info >  Download Data. From there, you want to download from Climate Daily/Forecast/Sun, 30 Year Normals (daily), & Extremes (daily). The row limit is per day, so, for example, 60 days gives you the previous 60 days worth of daily data. All of the above spreadsheets are incorporated in the graphics, but if you only wanted daily data, for example, you can quote out the normals and extremes.  

The xlsx files included will run the script, as is, up to the end of February with no issue, but you will have to update them at the beginning of each new month for the most up to date data. You will only have to make sure the titles are the same for the xlsx files as they are for the pandas imports. If so, you are ready to go. 

I also include a monthly recap of the meteorology involved in this data collection here, if interested. January's edition: 
https://open.substack.com/pub/antonfalco/p/hamilton-ontario-climatology-vs-2024?r=lmrru&utm_campaign=post&utm_medium=web

February edition: https://antonfalco.substack.com/p/hamiltons-february-climatology-vs
March edition: https://antonfalco.substack.com/p/hamiltons-march-climatology-vs-observed?r=lmrru&utm_campaign=post&utm_medium=web&triedRedirect=true
April edition: https://antonfalco.substack.com/p/hamiltons-april-climatology-vs-observed

An example of the year end recap from 2023 is below. I used the same style, but have updated the code and write up significantly from the previous year:
https://open.substack.com/pub/antonfalco/p/yhms-2023-vs-climatology-daily-and?r=lmrru&utm_campaign=post&utm_medium=web

Example outputs:

![output](https://github.com/antonfalco/2024-YHM-Weather/assets/108304747/1322379d-e7b6-4c53-8e39-7a9620f16f1c)

![output1](https://github.com/antonfalco/2024-YHM-Weather/assets/108304747/c7b953e0-b000-4716-b3bf-c38cbbf6a382)

![output2](https://github.com/antonfalco/2024-YHM-Weather/assets/108304747/15bbf2d1-7739-4980-9d2b-a60e2c3ff921)

![image](https://github.com/antonfalco/2024-YHM-Weather/assets/108304747/d3179c9a-4d63-4de8-b64e-3faf6a731e88)
