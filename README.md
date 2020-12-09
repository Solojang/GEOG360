# Summarizing time-series land cover change using Mapbiomas data

### Author: Aiyin Zhang, Jiang He, Li Xi
### Email: AiZhang@clarku.edu, Jianhe@clarku.edu, LXi@clarku.edu
### Date: 2020.12.9
### Data: The data we use is download from [mapbiosmas](https://mapbiomas.org/download).
### Reference: Pontius, R. G., Krithivasan, R., Sauls, L., Yan, Y., & Zhang, Y. (2017). Methods to summarize change among land categories across time intervals. Journal of Land Use Science, 12(4), 218–230. https://doi.org/10.1080/1747423X.2017.1338768

## Objective:
- Our objective is to develop methods that can summarize critical land change information from time-series land cover maps.
- We aim to create maps and graphs that are both innovative and able to effectively communicate important information that are helpful to our intended audiences beyond this semester, including the MapBiomas team, and potentially, remote sensing specialists and land change scientists. 

## Informations about Graph:
### Our graphs are developed to answer the following questions:
- What is the area of each land category for each time point?
- How much did each land category lost and gained over each time interval?
- Among the gross changes of each category, which land cover types did it gained from / lost to?
- Among the gross changes of each category, how much of them were temporary changes and how much of them did not lose or gain again?
- How do we know the pattern of changes? 

## Terms:
- Gain Once: Gain of category in the corresponding time interval that did not lose subsequently.
- Loss Once:  Loss of category in the corresponding time interval that did not gain subsequently. But can transit to other categories. 
- Temporary: Loss or Gain of category in the corresponding time interval that gained or loses again subsequently. 
