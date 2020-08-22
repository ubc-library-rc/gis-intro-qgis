---
layout: default
title: Geoprocessing Toolbox
parent: Hands On
nav_order: 6
---

# Geoprocessing Toolbox

## Count the number of Douglas Fir trees in each neighbourhood.
)In the Main Menu select **View - Panels - Processing Toolbox**. This is where you can find a large number of analytical and geoprocessing tools. *In case you can't find the **Processing Toolbox** option, [click here](Enable-Processing-plugin)

In the search, type "count points in polygon" and double-click the result.

**Polygons:** vanHoods (your input polygon layer)   
**Points:** vanDougFirs (your input points layer)   
**Count field name:** DougFirs (the name of the attribute that will have Doug Fir counts)

Click **Run**, then **Close** when the process has finished. *You will now have a new layer called **Count***. Take a look at the attribute table for this new layer.

Save this layer to your data folder by right-clicking and selecting **Export - Save Features As..**

**Format:** Esri Shapefile    
**File name:** navigate to the location of your project's data and save the file as **vanHoodsCount**.

## Enable Processing plugin
