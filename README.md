# Report
Our idea is to collect the bike share data and taxi rider data for the years 2020 and 2022. 2020 will serve as our year where travel has been affected by COVID-19 and 2022 will be our year where the effects from COVID-19. We will view each month individually and specifically in the peak months of COVID-19 in 2020 to see how travel has changed while people are trying to avoid cramped public transportation. Based on these findings, we will conclude how COVID-19 affected “for hire” transportation in DC.

While working with our data, we realized that the months January-March 2020 were missing the start times and end times for the bikes. Due to this complication and no way to add these times, we excluded January-March 2020 and January-March 2022 data from our graphs. We deemed this appropriate because, around April 2020, COVID-19 was strongly prevalent, which should be reflected in the data.

We discovered that the variable objectid does not refer to the number of passengers while working with the taxi data. We utilized the function mutate to construct a new column that calculates the number of taxi rides based on mileage. If the mileage is zero, no ride occurred. Below are the graphs for the 2020 and 2022 data files:

2020
![image](https://github.com/torresnr/bikeshare_23/assets/145371919/83adee53-382b-4930-83a0-b6472902d509)
2022
![image](https://github.com/torresnr/bikeshare_23/assets/145371919/684363c0-391d-4ec8-babb-4bee518f551d)

Our findings concluded that ...
