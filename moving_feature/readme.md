# QGIS Move Feature Plugin

With this plugin, it is possible to move features from one location to another. For correct results please be sure that the layer and the canvas have same coordinate reference system.


* The plugin can be downloaded from: <a href="https://plugins.qgis.org/plugins/moving_feature/" target="_blank">https://plugins.qgis.org/plugins/moving_feature/</a>


For this process, 4 method can be used:<br/>

### 1-) Provide layers for reference points.
In this method; one point layer that contains 1 feature(start reference point), one point layer that contains 1 feature(end reference point) and a layer(to be moved) must be provided.<br/>

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
After process the layer(to be moved) is moved to the target location based on given reference points.<br/>

<p align="left">
  <img width="600" src="../images/Result.PNG">
</p>
<br/>
