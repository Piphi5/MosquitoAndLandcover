# Mosquito And Landcover

This Jupyter Notebook gathers GLOBE Observer mosquito larvae data in conjunction with land cover classification data (from Collect Earth Online) and soil moisture and surface temperature data (from NASA's Soil Moisture Active Passive satellite through the AppEEARS service). 

Any land cover and mosquito larvae data within 2.5 km of each other are deemed coincident and then grouped. For each of these groups, surface temperature data and soil moisture data are gathered from the AppEEARS API. 

We are then able to build a correlational matrix of land cover and mosquito larvae and create time-series graphs comparing soil moisture and surface temperature with mosquito larvae. These graphs allow us to observe the impacts of environmental variables such as soil moisture, surface temperature, and land cover on the presence of mosquito larvae.

The code in this repository was part of a final research project for the 2020 NASA SEES Internship. The presentation of the project can be found here:
[![Watch the video](https://img.youtube.com/vi/Yhn5nuYMDH4/maxresdefault.jpg)](https://www.youtube.com/watch?v=Yhn5nuYMDH4&feature=youtu.be&t=11240)
