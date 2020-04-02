---
layout: default
title: Choropleth Map
parent: Hands On
nav_order: 7
---

# Create a Choropleth Map

In your layers panel, remove everything except your **vanHoodsCount** and **vanShoreline** layers.

Right-click your **vanHoodsCount** layer and select **Layer Properties**, then click the **Symbology** tab.

At the very top, click **Single Symbol** and change to **Graduated**. This will allow you to display graduated colours representing classes of attribute values.

**Column:** DougFirs    
**Legend Format:** Precision 0, Trim   
**Color Ramp:** pick a color ramp that looks like it would represent the prevalence of Douglas Firs.        
**Mode:** Natural Breaks (Jenks)    
**Classes:** 5    

Click **ok** and close the window.
