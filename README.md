# Surfs_Up
Jupyter Notebook / SQLLite

## Overview
After vacationing in Hawaii, I discovered my love of surfing. My passion was so overpowering that I had to find a way to live that dream 24/7! With that being said, I needed to find a way to make ends meet in Hawaii. I finally came up with the idea to open a Surf n' Shake which would not only commercialize surf products, but also sell ice-cream to both locals and visitors. I had some savings, but not enough to make the project happen, therefore I started looking for investors! After putting together a business plan, I contacted Mr. W. Avy, also a surf lover, and he was enthusiastic about the shop, but requested some weather analysis about the location - his request was mainly about the temperatures year-round, but I decided to pull data regards precipitation as well.

## Results
We queried temperature and precipitation in the months of June and December - there were many years available minimizing any effect that might happen in a given year. 

### Statistics for June x December
- Temperature-wise, there are not many differences in Hawaii year-round: the average in the month of June is 75F and in December, it is 71F;
- The 75-percentile and 25-percentile also proved to be somehow stable, being 77F and 73F in June and 74F and 69F in December;
- The average precipitation also appear not to oscillate much: the 75-percentile in June was 0.12 as opposed to 0.15 in December.

![StatJune](/resources/StatJune.png)
![StatDec](/resources/StatDec.png)

### Findings year-round
As a bonus, we created two plots: Average, Minimum and Maximum Average Temperature year round for all the supplied data - the average shows the temperature is fairly stable with very little oscillation.

![PlotTempYear](/resources/PlotTempYear.png)

The same approach was done with Precipitation - the plot clearly shows the rain does not seem to impose any risk to a surf & shake business: not only the minimum is zero, but the average is very close to zero!

![PlotPrecYear](/resources/PlotPrecYear.png)

Lastly, we created boxplots using the same data as in the previous two charts. It is very interesting to see an outlier in the precipitation chart, it was certainly an unusually rainy month!

![BoxPlotTempYear](/resources/BoxPlotTempYear.png)
![BoxPlotPrecYear](/resources/BoxPlotPrecYear.png)


## Summary
Weather-wise, Hawaii seems to have very good conditions to start a business like the one proposed: the temperatures are good and there is very little precipitation. Now, we must find a good location for the store and here we go, Hawaii!