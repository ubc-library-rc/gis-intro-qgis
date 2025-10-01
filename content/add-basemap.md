---
layout: default
title: Optional - Add Basemap
parent: Hands On
nav_order: 13
---

## OPTIONAL: Add basemap from web plugin

Even though Vancouver currently appears to be floating in a sea of white, your shapefile is georeferenced meaning QGIS knows where on Earth Vancouver is. Adding a basemap helps give your map spatial context. While this step is **not required** for this workshop, below are instructions to add a web-based basemap to your project. 

### Install Plugin
[QGIS plugins](https://plugins.qgis.org/) are user developed tools that extend QGIS functionality beyond the basics. To access basemaps, we'll first install the QuickMapServices plugin. Click on the **Plugin** menu at the top of your screen and select **Manage and Install Plugins...**
![Install plugin](install-plugin_20221024.png)   
   
In the dialogue box that opens, select **All** as a search category on the left and type "QuickMapServices" as one word. Install the plugin and close the dialogue box.
![quick map services](quickmapservices_20221026.png)

### Add Basemap
Now go to the **Web** menu at the top of your screen. You should see the QuickMapServices plugin. Hover over it and click "Settings" at the bottom of the menu that pops up. In the settings dialogue box go to the "More services" tab and click "Get contributed pack." Click **save** to close settings and return to the **Web** menu. This time when you hover over the QuickMapServices plugin you will see an array of basemap options. Select OpenStreetMap as your basemap. Like QGIS, [Open Street Map (OSM)](https://www.openstreetmap.org/about) is open source and user developed.   

Make sure to drag your basemap to the bottom in your Layers Panel. Remove the basemap at anytime by right clicking the layer and selecting "remove." 

![Add basemap](OSM-basemap_20221026.png)


If you find web-based maps interesting, check out the Research Commons' [Webmapping Workshop!](https://ubc-library-rc.github.io/gis-intro-leaflet/) 
{: .note}
