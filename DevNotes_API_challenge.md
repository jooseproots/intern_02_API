---
title: "DEVNOTES_API_challenge"
tags: ""
---

# Dev Notes for API challenge

### 08.02.2024

- tried out first requests

### 10.02.2024

- made requests for Estonia's and Finland's GDP
- made requests for Estonia's and Finland's forestry sector's value added
- graphed the ratio of forestry sector's value added and GDP over the years for both countries

### 13.02.2024

- made requests for Estonia's and Finland's area of forestry land
- made requests for Estonia's and Finland's area of strictly protected forests
- calculated and plotted value added per 1 ha of forestry area over the years

### 01.03.2024

- added comments regarding inflation, all values in today’s prices
- comments for quarterly value requests: Value 1 stands for yearly data, use "I", "II", "III", "IV" for quarterly values
- started y-axis from 0 on forestry sector’s value added to GDP plot

### 02.03.2024

- comments explaining of JSON query values
- links to API endpoints
- separated URL-s to base and endpoint

Different values for forestry sector’s value added in LUKE database?

Embedding intermediate results in markdown cells not possible in jupyter notebooks without extensions

### 04.03.2024

- Added classes to create JSON format API queries
- Replaced explicit JSON dictionaries with queries made by classes for all requests
- Wrote a sample run for using query classes for requests

HTTP status codes:

*1xx informational response* – the request was received, continuing process

*2xx successful* – the request was successfully received, understood, and accepted

*3xx redirection* – further action needs to be taken in order to complete the request

*4xx client error* – the request contains bad syntax or cannot be fulfilled

*5xx server error* – the server failed to fulfil an apparently valid request

### 05.03.2024

- used raise_for_status() to raise errors for unsuccessful requests
- added extra analysis using data for forestry sector’s value added from Luke database

could use “filter” = “top” in query for ambiguous range?
