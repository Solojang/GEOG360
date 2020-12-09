# Summarizing time-series land cover change using Mapbiomas data

### Author: Aiyin Zhang, Jiang He, Li Xi
### Email: AiZhang@clarku.edu, Jianhe@clarku.edu, LXi@clarku.edu
### Date: 2020.12.9
### Data: The data we use is download from [MapBiomas](https://mapbiomas.org/download).
### Reference: Pontius, R. G., Krithivasan, R., Sauls, L., Yan, Y., & Zhang, Y. (2017). Methods to summarize change among land categories across time intervals. Journal of Land Use Science, 12(4), 218–230. https://doi.org/10.1080/1747423X.2017.1338768

## Objective:
### We present methods to summarize temporal difference in a time series of land changes
- To develop methods that can summarize critical land change information from time-series land cover maps.
- To create maps and graphs that are both innovative and able to effectively communicate important information that are helpful to our intended audiences beyond this semester, including the MapBiomas team, and potentially, remote sensing specialists and land change scientists. 

## Informations about Graph:
### Our graphs are developed to answer the following questions:
- Throughout the time series, what is the most frequently appearing land category in each location?
- What is the area of each land category at each time point?
- How much did each land category lost and gained during each time interval?
- A particular category lost to and gained from which other categories?
- A particular category lost to and gained from which other categories?
- What is the amount of change over various time steps?

## Terms:
- Gain Once: Gain of category in the corresponding time interval that did not lose subsequently.
- Loss Once:  Loss of category in the corresponding time interval that did not gain subsequently. But can transit to other categories. 
- Temporary: Loss or Gain of category in the corresponding time interval that gained or loses again subsequently. 
- Persistence: Incidents = 0 implies States = 1 and means a pixel persists as a single category across all time intervals.
- One Incident: Incidents = 1 implies States = 2 and means a pixel experiences exactly one change.
- Toggle：Incidents > 1 and States = 2 means a pixel toggles back and forth between two categories, as can occur in cycles of growth and harvest.
- Multiple States:  States > 2 implies Incidents > 1 and means a pixel experiences more than two categories.
