# PyBer_Analysis

## Overview of the analysis
### Background
CEO, V. Isualize, not only has a super cool and apt name, but she is also a cool as she is a former programmer who started out at MathWorks and became a co-founder of PyBer. As new agents at PyBer, we wanted to impress her. This assignment was an oportunity to do just that: V. Isualize asked us to summarize the ride-sharing data by city type, then evaluat fares for each city type. We were lucky enough to have our manager, Omar, assist us with the visualizations. We coordinated with him to make sure we were producing the right deliverables and approaching the large datasets in the best way. 

###  Purpose
The purpose would be to establish insights about the differences between various types of markets (urban, suburban, or rural) and make them transferable for future reference, consideration, and presentations by decision-makers at PyBer. We would do so using Pandas (multiple dfs derived from a few .csv collections that are theen merged), multiple-line graphs, bubble charts, and other visualizations with matplotlib. 

In previous analyses, these decision-makers already gleaned items from similar projects where the focus was on average ride fare on the total number of rides per city on each city type, summarizing the df that produced whole foods, drivers and rides, average fare/ride, and the average fare/drivers on the challenges. This time, we are helping PyBer take their analysis further and making it more relevant to demographics that may not currently be a part of the clientelle. In essence, we are tasked to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.


## Results

The three city types we analyzed ride fare data on were (1) urban, (2) suburban, and (3) rural. There seems to be a strong pattern between the respective city type and number of rides, number of drivers, and average fares associated.

Ride-sharing data included 
- Total Rides: 
  • 125 Rural 
  • 625 Suburban
  • 1625 Urban 
- Total Drivers: 
  • 78 Rural 
  • 490 Suburban
  • 2405 Urban       
- Total Aggregate Fares by Month by City Type: 
  • $ 4327.93 Rural 
  • $ 19356.33 Suburban
  • $ 39854.38 Urban   
- Average Fare per Ride and Driver:
  - PER RIDE
  • $ 34.62 Rural 
  • $ 30.97 Suburban
  • $ 24.52 Urban  
   - PER Driver
  • $ 55.49 Rural 
  • $ 39.50 Suburban
  • $ 16.57 Urban
 

![Screen Shot 2021-10-13 at 8 24 43 PM](https://user-images.githubusercontent.com/82982952/137230415-be4c0265-591f-4644-9385-b405405ec6b1.png)



## Summary


A significant part of the company revenue is coming from the urban fares which is providing about 150% more income on on average on any given month as compared to the rural fares, as seen by the height of the yellow line in the graph above compared to the blue line on the lower end. This is true despite the fact that our analysis proved that the rural fares per ride were more expensive (on average $34.62 per ride for a Rural ride v. $24.53). This highlights a point that there are more rides being requested (because urban areas by definition have more poeple), or more rides availible by way of more drivers, or a combination of these in the urban area as opposed to the rural cities given that the lower fare rates are aggregated to a significantly bigger revenue. As seen above, the total rides requested  in this dataset for urban was 1625 v. just 125 for Rural.  Thus, because of the probable scarcity, theoretically, the rates in the rural area probably on first glance shouldn't come down, and a desperate passanger would pay whatever it takes to entice a driver to come to the rural area, especially if that trip tends to be longer and is probably meant to get into or out of an urban center.  Yet, if the company does not want to take a purely capitalisitc/opportunistic approach and truly wants to make their services more accessible, this practice can't continue.

Recommendation 1: One strategy might be to create a program assigning a rotation of drivers to be in certain urban areas at all times to lessen wait time, and lessen the distance to pay for the driver to get there to begin with, or simply finding a way to recruit local drivers that will focus mainly on local/short rural to rural trips. Pyber would have to navigate the issue of drivers rightfully wanting to compete for more rides and move into the urban centers to increase their personal income. As seen above under results, currently, based on this dataset, there is almost double the ammount of drivers competing for the rides in the urban area (i.e. 2405 to 1625). So even with the high demand, drivers are getting left out anyway competing for multiple smaller rides. This should be emphasized to show how moving out of their convinient zone may make business more lucrative for them (they could make around $55 per ride in a rural area compared to a little over $16 in an urban city). This means they could make the same ammount of money with more breaks if they are willing to drive out a little farther and stay in the rural zone until the end of their shift. 

Recommendation 2: At first maybe there could be a sign on bonus, or an emphasis on the fact that these rides tended to cost more, or a proposal that with more drivers and more familiarity of the service locally, more riders would chose to use PyBer in the rural centers to get to longer distances (rural to rural, not urban), which would lead to more expensive fares and less transitions/waiting/preparation for the driver throughout the day as opposed to many short ride. 

Recommendation 3: Pyber could run a recruitment campaign focusing on individuals who seek out working for PyBer as a side job type task so more people could get on the road as independant contractors and contribute to the greater success of the integration accross all areas without having an issue of them wanting to get as many rides as possible to sustain themselves on this income, which would undoubtedly lead to a migration to the urban center as the business is still so heavily concentrated in those zones, and again leave gaps in access.  




(Something to consider maybe if we want to take the anaylisis further https://stackoverflow.com/questions/65063058/convert-unix-timestamp-to-date-string-with-format-yyyy-mm-dd)
