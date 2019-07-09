# Citi Bike Analytics

## Summary

I aggregated the data found in the Citi Bike Trip History Logs to build a data dashboard in Tableau over the year 2018.

## Data Sources

I downloaded separate csv files for Citi Bike trip histories for each month in 2018 from <https://www.citibikenyc.com/system-data>.

## Data Aggregation

I uploaded each csv into Tableau desktop and created a Union so I could treat it as a single data source. Then I created multiple tables and graphs to inspect and analyze the data.

## Data Visualizations

### Starting and Ending Locations

I first created separate maps of all the locations used to rent and return CitiBikes. I used size and color to indicate the popularity of these stations by the number of trips starting/ending there. I then pulled out the top 10 stations, plotted them on a separate map, and indicated each's popularity using a bar chart.

It became readily apparent that the most popular locations to both start and end trips were located in midtown and lower Manhattan by a very large margin. Tourists using bikes to visit popular landmarks in the city, along with commuters and residents tending to business, would explain this phenomenon. Pershing Square North, a very centrally located hub, saw extremely high traffic. Additional rental locations near there, along with the other top rental sites, might be beneficial to address this high traffic. Moreover, the concentrated popularity of midtown and lower Manhattan locations demonstrates the importance of keeping bikes there well stocked and maintained.

Rental drop-off locations did show increased use across the rivers in Brooklyn and NJ. This may be due to visitors or commuters using CitiBikes to leave the city, even though they were not used to enter it. There may be room for growth by promoting the use of CitiBikes to enter the city instead of just for leaving it.

### Trips in 2018

I then created two bar charts to visualize the number of trips over 2018, separated by month. The first bar chart depicts the gross number of trips for each month with colors to indicate months that fall within the lowest, middle, and highest tiers. The second bar chart shows the difference in number of trips from the given month to the previous. An increase in trips is colored green and a decrease in trips is colored red.

It is immediately apparent that the most popular months to rent a bike occur in the Spring and Summer with a marked decrease in November lasting throughout the winter. It makes sense that people are less likely to ride bikes outside during colder months. To address this fall-off, it may be worthwhile to investigate the possibility of offering discounted rates during these times.

### Ridership - User Type

I created another bar chart mirroring the previous chart depicting a bar for each month; however, this time I used a stacked bar chart to indicate the type of user for the rentals. Green is used to depict the number of trips subscribers took along with a label of the percentage of the total trips are represented by this group. Yellow is used to indicate non-subscriber customers.

Subscribers comprised the vast majority of users for each month, with a percentage share as high as 99.32%. Non-subscriber customers were most likely to use rentals during the warmer months. It may be advantageous to run a special promotion during one of these months to get these customers to be subscribers.

### Ridership - Gender

I created one final bar chart mirroring the two previous, this time using a stacked bar chart to indicate the gender of each customer along with a label indicating the percentage share of riders each gender makes up in the given month.

Men are much more likely, about three times so, to use CitiBike than women. This breakdown remains consistent throughout the year, with a slight decrease in female usage during the winter.

It would be worthwhile to allocate resources to promote CitiBike usage to the female demographic, as this is a huge largely untapped market.

### Ridership - Age

I created four heatmaps, one for each season, indicating the popularity of CitiBike in each 10-year age group from under 20 to 60 and older. The share of ridership didn't vary much throughout the seasons. Riders in their 30's comprised the greatest share by age group, varying little from 30.28% to 31.15%. Riders in their 20's and 40's rank 2nd and 3rd depending on the season remaining in the low to mid-twenties percentages.

The most surprising observation is that the riders under the age of 20 comprise such a small percentage of the ridership that they barely register on the heatmap. Investigating this young demographic, perhaps targeting students, may be worthwhile.
