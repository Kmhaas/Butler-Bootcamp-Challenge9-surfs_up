# surfs_up

## Overview of the analysis: 
* The purpose of this analysis is for W. Avy, He wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. Using Python, Pandas functions and methods, and SQLAlchemy, I will filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. I will then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics for the months of June and December.


## Results: 
* The mean temperature for the month of June is roughly 75 degrees compared to December 71 degrees. Both temperatures are beneficial for business.
* The minimum temperature for the month of June is 64 degrees compared to December 56 degrees. December minimum temperature is much lower than June, business can slow during this time.
* The maximum temperature for the month of June is 85 degrees compared to December 83 degrees. Both tempertaures are beneficial for business.



![June Stats](https://user-images.githubusercontent.com/93004710/155856289-d2b461d3-76f0-49b7-a564-70849ed6e76d.png)
June Summary Statistics






![December Stats](https://user-images.githubusercontent.com/93004710/155856319-d5256c7f-1838-46b1-bdb9-362ae4edd5a6.png)
December Summary Statistics


## Summary: 
* Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
* The summary statistics from the months June and Decemeber, mean temperatures and max temperatures show warm enough weather to support sales for ice cream. December minimum temperature of 56 degrees might not seem like a cold day to the rest of the United States but in Oahu, Hawaii it is. On some of the colder days in December the demand for ice cream will not be as high as the warmer months. In December only one forth of the days are just below 70 degrees in Oahu resulting in the rest of the month staying warm enough for the demand for ice cream at the surf shop. Additional queries should be performed to gather more weather data for the months of June and December to determine if the surf and ice cream shop business is sustainable year-round
* An additional query to perform to gather more weather data for the months of June and December in Oahu, Hawaii would be for the percipitaion amount, and frequency. Rain for an entire week could seriously damage the ice cream side of the business and gathering more data will show how much rain the shop can be in for.
* An additional query to perform to gather more weather data for the months of June and Decemebr in Oahu, Hawaii would be surf forecasts. As a surf shop knowing the surf forecasts will help anticipate when the beach will be crowed for the waves and when they will be empty for the violent storms the waves also bring in.
