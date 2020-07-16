[Return Home](/README.md)
# Visualizations of Government Debt Across the World 

## Government Debt in 2018
<iframe src="https://data.oecd.org/chart/61IP" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/61IP" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>


## Individual Countries' Change in Debt ratio from 1995 to 2019

<div class="flourish-embed flourish-chart" data-src="visualisation/3180907" data-url="https://flo.uri.sh/visualisation/3180907/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Geographic Location of the Countries 
After looking at the above graphs to see a summary of government debt for countries in 2018 and their trends over the year, I wanted to visualize the location of the countries and see if that impacts the debt amount. Therefore, using the 2018 data year, as that was the most recent complete data for all the countries and to allow comparison against the first graph, I created a heatmap. 

Using the debt ratio as the variable, I am now able to see where each country is located along with their corresponding debt ratio in 2018. The darker the color, the higher their debt ratio for that year. You can hoover over any location to see the name of the country and its corresponding debt ratio, if available. Only 34 countries had data, thus the map is sparcely colored. But nonetheless it provides an interesting geographic alternative to the bar graph on this page. Not only can we easily see how the debt ratio compares across the different countries through color saturation variations, we can also see their location relative to each other. For example, in Europe, you can easily see grouping of countries: one cluster of countries with lower debt and a nearby cluster of countries with higher debt. This information wouldn't have been as easily noticable in the bar chart. 

<div class="flourish-embed flourish-map" data-src="visualisation/3190075" data-url="https://flo.uri.sh/visualisation/3190075/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The line chart graphs tells a different story as we are looking at historic trends within each country. To make this heat map a more comparable one, I would add the future enhancement for switching this heat map among the different years. This way, the user can select any years of interest and see how the debt ratio changes visually by location between the two years, instead of just seeing the number change. To mimic that visual, I added a 2008 version of the map for comparsion. By comparing the two maps of country debt ratio in 2008 vs 2018, we see modest increases for most countries similar to the line chart graph. 
However, by using the heat map we can also focus on one year at a time while looking at all the countries, which can be beneficial for understanding the point in time, with the ability to compare against an other point in time. The line chart graphs shows the different message of trends in time. The two types obviously has their own pro and con, such as point in time comparsions can miss out on opposing changes, such as a drop in debt ration, that will captured by a trend line. But on the pro side, it offers a clearer visual of that point in time. 

<div class="flourish-embed flourish-map" data-src="visualisation/3191405" data-url="https://flo.uri.sh/visualisation/3191405/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

