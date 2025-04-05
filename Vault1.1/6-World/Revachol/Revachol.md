---
map_height_y: 6616
map_width_x: 12800
scale_pixels: 50
scale_pixels_range: 50
mapCalc1: 10
NoteIcon: map
---

```leaflet
id: Revachol ### Must be unique with no spaces
image: [[Revachol.png]] ### Link to the map image file
bounds: [[0,0], [6616, 12800]] ### Size of the map in px Width_x, Height_y
height: 900px ### Size of the leaflet embed in px on your screen
width: 95% ### Size of the leaflet embed in your note
lat: 0 ### To center the map, make this half of the map width. 
long: 0 ### To center the map, make this half of the map height. 
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level. 
maxZoom: 1 ### Controls how far towards the map you can zoom in.  Hover over the target icon to see the current level. 
defaultZoom: -3 ### Sets the default zoom level when the map loads.  Hover over the target icon to see the current level. 
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out. 
unit: m ### The value displayed when measuring so you know what type of unit is being measure.
scale: .2 ### Real units/px (resolution) of your map
recenter: true
darkmode: false ### marker
```

> [!NOTE]- Quick Calculator
> Map Height in Pixels: `INPUT[number:map_height_y]`
Map Width in Pixels: `INPUT[number:map_width_x]`
lat: `VIEW[{map_height_y} / 2][math]` 
long: `VIEW[{map_width_x} / 2][math]` 
How Many Pixels In Scale: `INPUT[number:scale_pixels]`
How Many Units in Scale: `INPUT[number:scale_pixels_range]`
scale: `VIEW[1/{mapCalc1}][math]`