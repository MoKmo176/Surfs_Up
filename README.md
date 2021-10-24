# Surfs_Up

## Overview of Surfer Weather Analysis
### Purpose
The purpose of this analysis is to extract data using advanced techniques in SQLite and other dictionaries to output organized complete dataframes.  The temperature for Oahu is derived from the Hawaii SQLite dataset, and is organized to give the surf shop owners  better picture about the surf and ice cream business year around. Our data is segmented by the months June and December, so that Surfs Up can analyze the seasonal polarities to determine if the business is sustainable all year. 

## Results
- The data in June Temps shows higher average temperatures. There is also more temperature data counts in the month of June (1700).
![June Temps Data](https://github.com/MoKmo176/Surfs_Up/blob/5c941b246858edd52d4fc0a35cab3329de34de57/README%20Files/June%20Temps.png)
- The data in December Temps shows lower average temperatures and much lower minimum temperatures. There are less temperature data counts in December(1517).
![December Temps Data](https://github.com/MoKmo176/Surfs_Up/blob/5c941b246858edd52d4fc0a35cab3329de34de57/README%20Files/Dec%20Temps.png)
- All the data between June versus December suggests that the weather patterns only have a small difference in Average and Max Temperatures in June versus December. The Average temperature in June is about 75 degrees and the max temperature in June is 85 degrees. The average temperature in December is about 71 degreees and the max temperature in December is 83 degrees.

## Analysis Summary
The Temperature Year Around in Oahu is very similar with the exception of some colder minimum temperatures in December. The minimum temperatures are most likely at sunrise and sundown, and should not affect the sales of a Surf and Ice Cream shop operating in the heat of the day. 
1. An additional query of June and December temperatures can test the mid-day temperatures against end-day in each day of the month to find temperature spikes and optimal operating hours. 
2. An additional query of June and December temperatures can test the average legnth of temperatures above 75 degrees, this can help determine how many hours Oahu reaches ideal temperature for Surfing or Ice Cream. 

