# hiking-with-pastries

<h2>Data Sources</h2>
I utilized the data sets from
  https://www.census.gov/cgi-bin/geo/shapefiles/index.php for my county map and state map,
  https://trails-vdcr.hub.arcgis.com/search?groupIds=08ed5266d9e34b9599e879c2a90833fb for my trails and trailheads, and 
  OpenStreetMap QuickOSM for my coffee shops.

<h2>Why I created the map</h2>
I created the map because I plan on moving to Virginia soon, and in the morning before I go hiking I enjoy stopping by coffee shops and getting a pastry for breakfast. I wanted to know where the closeset coffee shop to every trailhead was so that I could plan accordingly.

<h2>Creating the map</h2>
<h4>To create the map I started by downloading a dataset from the TIGER/Line Shapefiles that showed the state boundaries, and a dataset that showed county lines. I then added those datasets as Vector layers and filtered them so that they only showed the state I was working on, which was Virginia.</h4> 
<h4>I then found the dataset for the trails and trailheads and added them as Vector layers as well.</h4>
<h4>After styling the map to make it more legible, I used QuickOSM and the Quick Query function to search for 'cuisine' = 'coffe_shop'</h4>
<h4>With all my data now present, I utilized the "Distance to nearest hub" function to connect each trailhead to its closest coffee shop</h4>
<h4>I then used the "Extract by location" function to remove all coffe shops that were not the closest shop to any trailheads</h4>
<h4>Finally I went through and readjusted the style of the map for appearence's sake. I changed the color of my hub lines to make them stand out more, and I changed my point markers to be SVG markers to make it more obvious at first glance what each point referred to</h4>
