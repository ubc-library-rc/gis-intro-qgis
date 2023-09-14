---
layout: default
title: Add Data
parent: Hands On
nav_order: 3
---

# Three Ways to Add Data

## 1. Connecting a Directory 

There are many ways to connect directories (folders) and add data to a QGIS project. Adding our working folder as a "favorite" connection now will make things easier later on. In the Browser Panel, right click **Favorites** and select **Add new directory**. Navigate to your newly extracted folder called **intro-qgis-project-files**. Select it (but don't click into it) and hit Open at the bottom right of the dialogue box. The directory **intro-qgis-project-files** is now pinned in your Browser Panel. Expand the directory by clicking the triangle and open the **data** folder.


![Image of Open VanTreeMap ](Open-vantreemap_20220518.png)



## 2.Data Source Manager 

On the toolbars at the top of your screen, click the **Layer** button and select **Data Source Manager**. You can also open **Data Source Manager** directly from your docked **Data Source Manager Toolbar**. 

![Data Source Manager button](data-source-manager_20220518.png)

Select the **Vector** tab. For the vector dataset's source, click the three dots and navigate to your **intro-qgis-project-files\data** folder. Select the file named **vanBigTrees.geojson**. Click **Add**, then **Close**.

![add vanBigTrees vector](add-vector-vanBigTrees_20220518.png)

*You should see a new layer named **vanBigTrees** in your Layers Panel, as well as dots on your map canvas symbolizing the coordinate location of some trees.*

![vanBigTrees new layer](vanBigTrees-new-layer_20220518.png)

## 3. Layer Menu

A third way to add layers to your map canvas is through the **Layer** button at the top of your page. Under **Layer**, navigate to **Add Layer** and select **Add Vector Layer...** . This will open the same **Data Source Manager** dialogue box as before. 

![Add Vector Layer](add-vector-layer_20220518.png)

There are often multiple ways to perform an action in QGIS. As you become familiar with the interface, you will find a workflow that suits you. 
