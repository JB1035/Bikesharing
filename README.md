# Overview

The purpose of this analysis is to understand trends from bike sharing-service, CitiBike, looking at data from August 2019 in NYC, to determine if a similar program can be open in Des Moines, Iowa. August is the busiest month of the year for bikesharing in NYC and was therefore used for the analysis.

Data was retrieved from Citbike's public website as a CSV and then updated in Jupyter Notebook using Pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype in hours and minutes. An updated CSV file was then uploaded to Tableau in order to visualize and analyze the data. 

**Sources:** 
* Data: https://citibikenyc.com/system-data -> 201908-citibike-tripdata.csv
* Software: Tableau Public, Jupyter Notebook, Pandas

# Results

The data is summarized as a story / presentation in Tableau Public via the link below:

https://public.tableau.com/app/profile/jennifer.barrios/viz/shared/K56YF8C2B

Key Findings by Visualization: 
* Total Number of Rides: 2,344,244
* Checkout Times for Users: Most checkouts last for less than an hour, with mos rides lasting 10 min for 140k riders 20 min for 40k riders.
* Trips by Weekday per Hour: Thursdays and Saturdays are the busiest days from with rides most between 7am-8pm.
* Gender Breakout: The majority of riders (65%) are male.
* Trips by Gender (Weekday/Hr): Males and females follow similar usage patterns by weekday. The busiest times are 8am M-F, and 5-7pm M-F.
* Checkout Times by Gender: Both males and females tripduration mostly last for less than an hour, with most rides at 10 min.
* Usertype Breakout: More than half (81%) of usertypes are subscribers vs customers.
* User Trips by Usertype by Gender by Weekday: Thursdays is the busiset day of the week among male and female subscriber types, followed by Friday, Tuesday, Monday. 

# Summary

Considering the lower usage times of less than an hour for most bikerides, which also take place mostly during the week, among subscribers, vs customers, means that business is likely being driven mostly by locals commuting within the city vs tourist. To understand if this model could work in a less densly populated area such as Des Moines, it would be worth analyzing: 
* Average tripduration times by age.
* Trip duration times by usertype, by gender by age.
 
