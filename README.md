# Lab 6 - Seattle Collision Smart Dashboard

**Dashboard Website: https://eddiep7.github.io/GEOG458_CollisionsDashboard/index.html**

**Datasource:** https://data-seattlecitygis.opendata.arcgis.com/datasets/34dd0a126aeb4dd5b99a397b5884e71f

### Project Details:

The dashboard I created provides information on collisions and accidents in the Seattle area from 2004 to the present day. On the dashboard, users can view details such as the specific type of collision and the number of fatalities for a particular incident by clicking on a location represented by red circles on the map.

To visualize the different scales of collisions, I chose to use a proportional symbol representation with circles becoming larger depending on the number of fatalities in an incident (larger circles indicating greater fatalities). I opted for this over a choropleth map because, after experimenting with both, I found that representing circles in specific areas was much clearer, especially when examining specific streets. The visualization was easy to read, taking inspiration from earthquake examples.

Based on what you see on the map, the sidebar provides information on the total number of collisions and total fatalities shown on the map, along with an included bar chart representing this information.

Please note that when creating this website, the data source we used was filtered to include only incidents with fatalities. This was necessary because the original dataset was too large for GitHub to handle. Even when using external applications, the website did not handle the large dataset well.

- Mapbox GL JS (for interactive maps):<br>
&nbsp;&nbsp;Library Link: https://api.mapbox.com/mapbox-gl-js/v2.8.1/mapbox-gl.js<br>
&nbsp;&nbsp;Stylesheet Link: https://api.mapbox.com/mapbox-gl-js/v2.8.1/mapbox-gl.css
- Chart.js (for creating charts):<br>
&nbsp;&nbsp;Library Link: https://cdn.jsdelivr.net/npm/chart.js
