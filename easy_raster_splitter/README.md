# QGIS Easy Raster Splitter Plugin

### Installing third party Python libraries to QGIS
If you need to install opencv module manually you can follow the steps below.<br/>
1-) Open OSGeo4W Shell as an administrator,<br/>
2-) Type py3_env in the console (This should print paths of your QGIS Python installation),<br/>
3-) Type python -m pip install {your library}<br/>
"python -m pip install opencv-python"<br/>
<sub>*Source:https://gis.stackexchange.com/questions/141320/installing-3rd-party-python-libraries-for-qgis-on-windows*</sub><br/><br/>


With this plugin, it is possible to split raster files based on given polygon data. For correct results please be sure that the layer and the canvas have the same coordinate reference system.

2 methods and 2 options are available for this process<br/>

An illustrative example is shown below:
<br/>

<p align="left">
  <img width="750" src="../images/img.PNG">
</p>
<br/>

### 1-) Clip method.
In this method; the input raster is clipped by the provided polygon data(in vector format). After the process, the clipped parts are kept.<br/>
#### a-) Split By Feature
The raster is clipped by features seperately. The names of the created rasters are read from the attribute table of the polygon data.

<table>
  <tr>
    <td><img width="450" src="../images/clip by features.PNG"></td>
    <td><img width="450" src="../images/clip by features example.PNG"></td>
  </tr>
</table>

#### b-) Split By Full Vector
The raster is clipped by full vector. The names of the created raster is typed manually.

<table>
  <tr>
    <td><img width="450" src="../images/clip by full vector.PNG"></td>
    <td><img width="450" src="../images/clip by full vector example.PNG"></td>
  </tr>
</table>


### 2-)Extract method.
In this method; the input raster is extracted by the provided polygon data(in vector format). After the process, the extracted parts are deleted.<br/>

#### a-) Extract By Feature
The raster is extracted by features seperately. The names of the created rasters are read from the attribute table of the polygon data.

<table>
  <tr>
    <td><img width="450" src="../images/extract by features.PNG"></td>
    <td><img width="450" src="../images/extract by features example.PNG"></td>
  </tr>
</table>

#### b-) Extract By Full Vector
The raster is extracted by full vector. The names of the created raster is typed manually.

<table>
  <tr>
    <td><img width="450" src="../images/extract by full vector.PNG"></td>
    <td><img width="450" src="../images/extract by full vector example.PNG"></td>
  </tr>
</table>


