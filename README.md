## NC Wildlife Resource Commission Game Land and Boat Access Map
<BR>
  
***About The Map***\
This map shows three different types of public boating access points (Coastal, Inland, and Joint) owned by the North Carolina Wildlife Resource Commission (NCWRC) and how many are on each gameland designation, if any.  Focus is on the tidewater region since access types can vary along the sounds and coastal islands.

***Functions***\
I have added a click event on the boat access points to get the address from each location.  I would love to find a way to add a "Get Directions" button that is linked to Google Maps.

***Libraries***
* leaflet-ajax for GeoJSON
* chroma.js for colors
* Google fonts for the use of *Oswald*
* leaflet for basemap
* jquery javascript
* Font Awesome for *ship* icon

***Data Sources***\
Both the boat access points and gameland designations are courtesy of NCWRC and the shapefiles are available to download at NC One Map.

The basemap is from Stamen Designs and is available at http://leaflet-extras.github.io/leaflet-providers/preview/

***Future Features***\
I was initially trying to make make multiple classes within each Gameland Designation.  For instance, the Game Land designation would be multiple shades of green corresponding to the number of boating areas within each boundary.  

I will for sure be coming back to this map to try and get my multiple class choropleth feature to work properly.
