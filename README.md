# PyBer_Analysis #

## **Project Overview** ##

A python based ride-sharing app company, "PyBer" has asked for a an anlysis on the data collected for rides based on city type. Pyber is looking to create more access to their ride sharing services and determine their affordability. Visulaization was performed by way of scatter plots, box-and-whisker plots, pie charts and line graphs on the gathered data from CSV files. We gathered distribuiton information and will view below. 


**Software Used**

Python

Jupyter Notebook

Matplotlib

Pandas

## **Results** ##

Overall, results show that there is a higher concentration of drivers and riders in the Urban cities. While the lowest concentration of riders and drivers is in Rural cities/towns. Suburban city types fall somewhere in between. The average fares for Rural areas are the highest and the Urban areas are the lowest. We also see that the average pay per driver is the highest in rural areas, and the lowest in Urban areas. Suburban areas fall in between for all categories but the data suggest that Suburban is more similar to the rural city types.



The pie charts below show the percentages of riders and drivers in each city type of all the ride info collected:

![Fig6](https://user-images.githubusercontent.com/99927324/164956609-5bfda461-dbb4-443b-adff-59c5485fa7b2.png)

![Fig7](https://user-images.githubusercontent.com/99927324/164956612-04d20a0f-f0a6-4c05-977b-f4822fc7fee8.png)

We are  able to see that the Urban Cities account for more than half of the rides and drivers of the 3 city types. 

Taking a deeper look, below we have a scatter plot showing the average fare amount and the number of rides by the city type
Here, we see that the Rural city types have the highest fares on average and the lowest ride rates of the 3 city types

![Fig1](https://user-images.githubusercontent.com/99927324/164956666-d16547e6-9bd0-4d24-9ea1-93f7e18def8d.png)




This figure shows the total number of rides, drives, total fares spent on rides, average fares per ride and the average pay to drivers-based on city type:

![image](https://user-images.githubusercontent.com/99927324/164956780-dcfdaf85-280a-48a1-a497-cad6b0a68c1f.png)





## **Summary** ##

**Urban Cities**

The Urban cities account for about 68% of the total rides by city type but the number of drivers makes up ~80% of the total drivers. There are about 1.5 x the number of drivers than riders. We would expect to see percentages that more closely resemble each other like we see with rural rides. This suggests that the Urban cities, overall, may have too many drivers. If there are drivers idling and missing rides due to a low demand with respect to available drivers, the CEO may want to attemp to divert some of these drivers to the suburban cities.

**Suburban Cities**

The data collected suggests that there are not enough drivers in these areas. At ~30% of the total rides, the percentage of drivers being at about a 4th of total drivers does not seem to be a good model. When looking at the dataframe,we see when compared to Urban and Rural cities, there is the most impactful disparity between rides and drivers. This is likely what is driving up the price for riders in this area as they are more simlar to rural prices than urban prices. Based on knowledge of city types, one would expect that the price be more similar to the urban areas because they are more similar to one another.

**Rural Cities**
Based on the data, the amount of drivers in the rural areas is at about where it should be. There is not a significant difference between the rides and drivers in these areas. The percentages of Drivers and Rides are about the same as seen in the pie chart above. This suggests there is eqilibrium. 


In conclusion, I would advise the CEO to decrease the number of drivers in the Urban areas, increase the number of drivers in the Suburban areas, and to effectively, leave the drivers in the rural areas as they are. 

I would also see if they have data or could gather data about why the rural areas are as low as they are. The price point and available drivers could be discouraging people from opting for thir service. It may be worth looking into because the prices, when compared to urban areas, are not affordable.

