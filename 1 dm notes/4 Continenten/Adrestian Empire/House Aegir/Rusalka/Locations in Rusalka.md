
**Rusalka** is a small territory to the west of boramas, filled with lakes and a small City. The area is home to all sorts of wandering monsters, demonic or otherwise, making it a good place for hunters to find good (if dangerous) work. The area was originally ruled by house Martritz, but when the house was abolished it was taken in by Aegir, who imposed taxes on the land and otherwise let it run itself



 ```leaflet  
id: Rusalka city ### Must be unique with no spaces  
image: [[Rusalka.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [6144, 8192]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 600px ### Size of the leaflet embed in px on your screen  
width: 120% ### Size of the leaflet embed in your note  
lat: 4090 ### To center the map, make this half of the map height.  
long: 3550 ### To center the map, make this half of the map width.  
minZoom: -4 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: -1.5 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -3 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
