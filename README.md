# PyBer_Analysis
## Overview
We have been given data from a ride-sharing company in the form of two datasets with data detailing the number of drivers in a city, the type of city (Urban, Rural, or Suburban) and information regarding the actual transactions and fares and dates during which those transasctions occurred.  Both datasets ("city_data.csv" and "ride_data.csv") are available in the resources folder.  For this analysis we are interested in primarily in total weekly fares and several other metrics and how these vary by city type. Analysis is contained in the PyBer_Challenge.ipynb notebook.  
### Results  
After combining the datasets into a single frame and generating summary statistics based on the type of city in which the transactions took place, several differences become evident.  Urban cities clearly have the highest number of transactions for the reporting period with  more than double that of Suburban locales and ten-fold that of rural locales. Likewise, Urban communities have a higher number of drivers available than Suburban and Rural communities by at least five-fold.  Not surprisingly the differences in driver availability and total rides are reflected in the average fares per ride and driver, with Suburban and Rural communities having generally higher ride fares and driver fares compared to Urban communities. The highest fares are found in the Rural communities as expected.  

Summary statisitics by City/Community type:  

![fare_summary](https://user-images.githubusercontent.com/60231630/139134842-4fe8bc1b-b85b-401f-a1e8-b7125bc00755.png)  

An analysis of total weekly fares over a four month period beginning in January-2019 shows Urban communities exhibiting the greatest total fares overall throughout the four month period with Rural communities having the lowest fares. A consistent increase in weekly fares is noted in all three community types during the third week of February:  


![PyBer_fare_summary](https://user-images.githubusercontent.com/60231630/139135970-7353e53d-cd65-40c9-afc1-b2e26b39e497.png)  

### Summary  
The cause of these disparities stems primarily from the lack of drivers in Rural communities which coupled with demand results in higher fares.  Hiring more drivers in Rural communities might offset this and reduce overall fares in these areas. However, Rural drivers also likely have to drive further distances which in turn results in higher fares and so this issue may need to be addressed. Indeed, additional data collection on driving distances and how that affects fares in all three communities may be warranted.  On the opposite hand, if one desires to maximize fares in Urban and Suburban communities, then changing the ratio between total rides and total drivers by cutting the number of drivers might be warranted to increase total fares however such a change would likely be offset by the decrease in the number of transactions.  Finally, weekly fare totals appear to peak during certain times of the year. Adjusting fare prices and number of drivers during those times (i.e during late February for instance) may help to maximize profit or offset some of the disparities.
