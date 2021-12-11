suitable places for establishment of town



I am trying to locate a place that is best suitable to establish a town. This is an area in Southern Illinois in the United States. For this, I have included major rivers, roads, existing urban areas, protected areas, flood plain, and a digital elevation model. I found these data from UC Davis Extension.

First I created a constant raster of value 1 (set environment settings like extent processing, snap, clip, coordinate system same as dem layer) and converted it into a vector layer. Then I used a buffer tool to create 1500 buffer to roads and 1000m buffer to major rivers. After that, I created slope raster from dem and created slope raster of slope less than 5 degrees using the raster calculator and converted it vector layer.

For the area I don't want my new town to be in like flood plain areas, protected areas and existing urban areas, I used erase tool multiple times to remove the area one by one from my constant vector layer. After that, i used intersection tool several times to intersect areas like buffered roads, buffered rivers and slope less than 5 layer. Finally, i plotted area on map with required details.

The result shows an area where a new town can be established. These areas are near roads, river, have slope less than 5 degrees and are not in an existing urban area, flood plains and protected areas which makes it suitable for a new town.
