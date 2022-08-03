# Hacking-Attempts-Geodata

# About the Dataset

This dataset contains date and time of attempts on an Australian website. The data was collected using fail2ban logs on a set of pre-defined rules as to what was considered a hacking attempt, such as multiple failed login retries, repeated attempt to hit particular pages or applications that did not exist. The data included an IP address, which was then transformed in to geospatial co-ordinates - as such, spoofed IP addresses or VPN use may skew results.

Timestamps in AEST (GMT+10) format and cover 21 August 2021 to 13 July 2022

# Dataset files

The dataset contains one csv file with three distinct columns:

1. lat - Latitude: The lattitude for the location of the attempted breach
2. lng - Longitude: The Longitude for the location of the attempted breach
3. datetime - time stamp corresponding to location with date

# Data source

The data can be accessed on Kaggle: https://www.kaggle.com/datasets/tastyworm/geodata-for-hacking-attempts.

# Analysis Objectives

1. Plot the data on a map of all the hacking locations
2. Determine location with the highest number of breach counts.
3. Determine the month with the highest number of breaches.
4. Determine the date with the highest number of breaches

# Observations and Findings

1. No hacking attempts were recorded to originate from Australia
2. There are relatively few hacking attempts originating from the South American and African Continents
3. There are some hacking attempts not located within mainland continents. A likely indication of hacking attampts from Islands or cruise ships
4. The majority of the hacking attempts are from Asia, Europe amd North America. The coodiantes with the highest recorded number of breaches os: [39.9075, 116.3972] in mainland China, with a recorded 4218 hacking attempts

# Tableau Dashboard

The Dashboard for this project can be reviewed on Tableau Public: https://public.tableau.com/views/HackingGeodata/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
