# MonarchButterflyWebMap
Monarch Butterfly Adult Sighting Map for the Fall 2018 Southern Migration <br>
[Map Link](https://jagreen1.github.io/MonarchButterflyWebMap/JAG_Geob472_Lab1_v4.html)

This webmap displays location data for reported first sightings of adult Monarch Butterflies in 2018. The slider in the upper left can be used to filter data between August 1, 2018 and December 31, 2018. Data points can be clicked on to reveal metadata about the sighting events.

## Webmap Screenshot
![Example Map Screenshot](https://jagreen1.github.io/MonarchButterflyWebMap/Example_WebMap_Screenshot.PNG)

## Mapbox Studio JSON style file
[Custom Map Style](https://jagreen1.github.io/MonarchButterflyWebMap/Minimalist-Environmental_Style.json) <br>
This map features a custom map style developed in Mapbox Studio.

## Data
[Data Source](https://journeynorth.org/sightings/querylist.html?season=fall&map=monarch-adult-fall&year=2018&submit=View+Data) <br>
[Monarch Sighting Geojson Data](https://jagreen1.github.io/MonarchButterflyWebMap/2018MonarchSightings.geojson) <br>

First adult monarch butterfly sighting data from 2018 was obtained from the 'Journey North' citizen science website. Data from public reported sightings between August 1, 2018 and December 31, 2018 were entered into a csv file. The data was then converted into a geojson feature collection following the WGS84 GCS, using the Open Data Institute's 'CSV to GeoJSON' webtool. 

[Monarch Butterfly Image](https://www.hiclipart.com/free-transparent-background-png-clipart-qdsai) <br>
The copyright-free monarch butterfly image used to represent the data points was obtained from (https://www.hiclipart.com/). <br>


## Reflective analysis:
I have designed an interactive web map that displays monarch butterfly (Danaus plexippus) first adult sightings data in the fall and winter of 2018 as point features. The map is focused on North America with the majority of data points being located in the United States, Canada, and Mexico. It features a slider bar that allows the user to filter through the sighting data time series from August 1st to December 31st.  The data points appear as monarch butterfly images, and when clicked on a popup window is displayed containing metadata about the sighting event including the date, town, and province or state. This map is intended to help wildlife conservation scientists and monarch butterfly enthusiasts visualize the monarch butterfly’s annual southern migration before winter in the northern hemisphere. 

When creating the map I choose to apply a minimalistic-environmental style that emphasized the butterfly sighting data points. This required using light and low saturated coloration, few place labels and icons, and limiting land cover and land use layers to forests, parks, and greenspaces.  The map is meant to be viewed at a large spatial scale, so when zoomed out the terrain is pale green and white. This allows the bright orange butterfly data points to stand out. Hillshade and 3D elevation used to provide a sense of terrain and highlight the inverse relationship between butterfly distribution and high elevation. Although the map is best viewed at a large scale, I designed the land cover and land use layers such that if you zoom to a smaller scale the greenspaces, forests, and parks appear in light green. These land class layers provide context and help explain the locations of butterflying sightings. I found that at a small spatial scale the high number of place labels and icons heavily littered the map and provided for a poor viewing experience. As a result, I choose to omit labels and icons for buildings, roads, or settlements as they were irrelevant to the environmental theme and took focus away from the butterfly points. Overall I believe my choice of minimalist stylization worked well for showing the butterfly migrations, as it places focus on the two key variables of terrain and data. 

Taking this map forward, I would implement additional technical features such as a play button that loops through the butterfly data points or a legend with background information and links to the data source. I would also look into including a polygon layer showing the species coverage of common milkweed (Asclepias syriaca), the primary host of the monarch butterfly.


Paragraph describing your map critique sessions as well as any other collaborations or help: A paragraph that describes any help you received or offered others, including how you responded to your critique session.
- received no help



