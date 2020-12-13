# QGIS Easy Raster Splitter Plugin

With this plugin, it is possible to split raster files based on given polygon data. For correct results please be sure that the layer and the canvas have same coordinate reference system.

2 methods and 2 options is available for this process<br/>

An illustrative example is shown below:
<br/>

<p align="left">
  <img width="750" src="../images/img.PNG">
</p>
<br/>

### 1-) Clip method.
In this method; the input raster is clipped by the provided polygon data(in vector format). After the process, the clipped parts remain.<br/>
#### a-) Split By Feature
The raster is clipped by features seperately. The names of the created rasters are read from the attribute table of the polygon data.

<p align="left">
  <img width="350" src="../images/Reference Points From Layer.PNG">
</p>
<br/>

### 2-)Provide coordinates for reference points by typing manually.
In this method; the coordinates for start reference point and end reference point must be typed manually and a layer(to be moved) must be provided.<br/>

<p align="left">
  <img width="350" src="../images/Type Coordinates.PNG">
</p>
<br/>

### 3-) Provide Δx and Δy values by typing manually.
In this method; the horizontal(Δx) and vertical(Δy) differences between start and end point must be typed manually and a layer(to be moved) must be provided.<br/>

<p align="left">
  <img width="350" src="../images/Type dx and dy.PNG">
</p>
<br/>

### 4-) Provide reference points by selecting them from canvas.
In this method; start reference point and end reference point must be selected from canvas and a layer(to be moved) must be provided.<br/>

<p align="left">
  <img width="350" src="../images/Select Reference Points From Canvas.PNG">
</p>
<br/>

### The result output:
After the process, the layer(to be moved) is moved to the target location based on given reference points.<br/>

<p align="left">
  <img width="600" src="../images/Result.PNG">
</p>
<br/>
