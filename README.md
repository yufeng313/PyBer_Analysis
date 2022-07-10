# PyBer_Analysis
Graph data using the Matplotlib library
## Overview of PyBer Analysis
In this challenge, I’m going to create a summary DataFrame to calculate total rides, total drivers and total fares as well as average fares of each city type, and then create a multiple-line graph to show the total weekly fares of each city type. Finally, I will use a report to describe how these data differs by city type and how those differences can be used by decision-makers at PyBer.
## Resources
Data source: city_data.csv, ride_data.csv<br/>
Software: Python 3.7.6   Jupyter Notebook 6.4.8
## PyBer Analysis Results
1.Create a summary DataFrame to calculate total rides, total drivers and total fares as well as average fares of each city type:
![pyber summary](https://user-images.githubusercontent.com/107179765/178158831-73fd33e9-1492-452e-ac64-7a7b03f5e085.png)<br/>
From the PyBer summary DataFrame, we can see that:
- Urban cities have the highest total rides and total drivers while rural cities have the lowest total rides and total drivers, which means urban cities have greatest demands on ride-sharing than other two city types. 
- As for the total fares, urban cities have the most revenue for PyBer company.
- The number of total drivers(2,405) is much greater than the number of total rides(1,625) in urban cities, this shows us some drivers in urban cities maybe never have a ride during those days.
- Rural cities have the highest average fare per ride while urban cities have the lowest average fare per ride, we can conclude that rural cities always have longer trips than other two city types. 
- The average fare per driver of rural cities is higher than other two city types, this may because of the driver driving for a longer distance, or driving for more rides than others.<br/>

2.Create a multiple-line graph to show the total weekly fares of each city type from 2019-01-01 to 2019-04-28:
![multiple-line graph](https://user-images.githubusercontent.com/107179765/178158842-99c9efd6-a0d2-41c6-8d30-db07bdd8e4f9.png)<br/>
From the line graph, we can see that:
- The weekly fares of rural cities are at the range: $0-500. The weekly fares of suburban cities are at the range: $500-1500. The weekly fares of urban cities are at the range: $1500-2500. Urban cities have the highest weekly fares, while rural cities have the lowest weekly fares. The weekly fares of urban cities and Suburban cities is 3+ times and 2+ times higher than rural cities.
- The trends of the total fares by each city type almost have the same ups and downs.
## PyBer Analysis Summary
Based on the results, I’ll offer three business recommendations to the CEO for addressing any disparities among the city types:
1. While the total rides are higher in urban markets, the average fares show that suburban and rural markets have a great demands that can be met with more drivers. Since the number of total drivers(2,405) is much greater than the number of total rides(1,625) in urban cities, I recommend researching ways to incentivize drivers away from urban markets and toward to rural / suburban markets to help balance the discrepancy. 
2. Weekly rides per driver ratio could be very helpful in tracking their effectiveness. Surprisingly, current rides per driver ratios are more in rural areas than in urban areas. This indicates that there are more drivers available in urban areas.
3. The multiple-line graph shows at least one very clear surge in late February in each city type. Optimizing price by that time will allow more profit for Pyber company and its drivers.
4. Increasing advertising in densely populated urban areas to attract new more customers will be an effective strategy for PyBer, as well as the suburban and rural markets, we can offer promotional discounts for repeating customers, and Pyber Credits for new customers.
