# NYC_Citibike_Analysis

## Overview & Purpose
The purpose of the following analysis was to investigate Citi Bike (New York City bike share program) data using visualization techniques held within Tableau. Specifically, the analysis looked at ride duration by gender, daily ride behavior by gender and the most common pick-up and drop-off locations for riders.

The goal was to create a compelling visual story which can effectively describe to the audience what the Cibi Bike rider behavior is like in New York City.

## Procedure
1) Download the Citi Bike Share data from: https://ride.citibikenyc.com/system-data
2) Using Python, create a Data Frame and convert the "tripduration" column into the ```datetime``` format so that it can be used for the Tableau analysis.
3) Create 7 charts to be used in the Citi Bike analysis:
    -  Trip duration chart which shows number of rides by their trip duration in bins of 1 hour.
    -  Trip duration chart by gender.
    -  Chart of trip starttime by day of week and time of day.
    -  Chart of trip starttime by day of week, time of day and by gender.
    -  Chart comparing customer vs subscriber.
    -  Map of pick-up locations.
    -  Map of drop-off locations.
 4) Create a Tableau Story using the created charts.

## Analysis & Results
Plase find the accompanying ```NYC_Citibike_Challenge.ipynb``` file to view how the data type of the duration data was converted using Python Panda data frames.

See Tableau analysis [HERE](https://public.tableau.com/app/profile/marc.corti/viz/GWCitiBikeChallenge/CitiBikeStory)

## Summary
From the Citi Bike analysis, there are some clear results:
1) Males make up the vast majority of all rides of the program.
2) Ride duration is typically under 1 hour. This is consistent with a program that costs more the longer you ride and the use of these bikes as a means to commute to work.
3) The bikes are mostly used M-F as a means to commute.
4) Subscribers make up most of the riders.
5) Pick-up and drop-off locations are concentrated in midtown and lower Manhattan.

The above results are consistent with the use of the bikes as a means of commuting over short distances in midtown and lower Manhattan.

Additional analysis could involve:
1) Map of Pick-up and drop-off locations by day of week. The hypothesis is the pick-up and drop-off locations on Saturday and Sunday would be more prevelant around Central Park compared to midtown and lower Manhattan M-F.
2) Age of rider compared to trip duration and day of week. Hypothesis would be M-F the rider age would swing younger due to commuting practices.
