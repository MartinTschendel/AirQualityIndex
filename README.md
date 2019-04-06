# AirQualityIndex
Gathering and Analyzing Data from the World Air Quality Index Project

The first goals are to understand:
* What a Web API is
* Learn how to use the HTTP request GET with JavaScript
* How create and display HTML elements with JavaScript

This [web-page](https://www.taniarascia.com/how-to-connect-to-an-api-with-javascript/) is hopefully helpful to proceed 

I understand there is a html page what provides a user surface. The js script sends a request to the AQI page and we get a json back. Now this json has to be ideally converted to a csv. The data from the csv can be further analyzed.

19-03-28: managed it to get a json file via the requests library

19-03-29: extracted data from json file and inserted it into pandas dataframe

19-03-30: tried to write a time loop and append new rows to dataframe

19-04-02: found a method to append new rows to dataframe; still don't know how to harmonize the columns (small project for next days:))

19-04-05: harmonized the columns (final data frame has three columns (City, Time, AQI) and respective values
