# <span style= "color:darkgreen">Road Trip to Raleigh!</span>🚘🎤 👯

<iframe src="index.html" height="500" width="500"></iframe>

You can explore the map [here](index.html)

#### <span style= "#FF0D65">Lab 03 Deliverable for GHY 5818</span>
Sarah Ulrich

<img src= "https://assets.livenationcdn.com/uploads/ritz_1024x576.jpg?auto=webp&quality=70&width=384" width=250/>

This map is of a driving route from my parking spot in the Queen Street parking lot in Boone, NC to the Ritz concert venue in Raleigh, NC. Along the way, I like to stop at the Sheetz in Yadkinville for refreshments, and gas if needed--this is the closest Sheetz gas station to Boone, about an hour outside town. My next stop is at my dad and stepmother's house, which is along the way in Jamestown, NC. My last stop before reaching my final destination is Med Deli on Franklin Street in Chapel Hill, NC where I plan to eat dinner before the concert. 

#### <span style="color: #ff9d00">Functions</span>

This webmap is structured using HTML. CSS is used within the <*style*> tags with JavaScript is used within the <*script*> tags. CSS provides color and style to the text and background elements of elements of my webmap. Using JavaScript, I loaded basemap data from <a href="https://leaflet-extras.github.io/leaflet-providers/preview/"><span style="color:#339966">Leaflet</span></a> and created a Leaflet map object. I also used *js* to add the GeoJSON file of my driving route as a variable named "data." JavaScript also allowed me to add some fun elements to the web map, such as using *mouseenter* and *mouseleave* to change background and border colors with the movement of my cursor on the webmap text. 
       
## <span style="color:#339966">Data & Libraries</span>
The basemap used in this project came from the Leaflet library. 
<a href="https://www.w3schools.com/cssref/index.php"><span style="color:#339966">W3Schools</span></a> for css styling functions. 
Route data came from Google Maps and <a href="https://mapstogpx.com/"><span style="color:#339966">Maps to GPX</span></a> was used to convert Google Directions into a GPX file. The GPX file was converted into a JSON file using <a href="https://geojson.io/#map=7.82/36.016/-80.153"><span style="color:#339966">geojson.io</span></a> The resulting .json file was used to create the web map. 
