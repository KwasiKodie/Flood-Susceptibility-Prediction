<h1>Flood Susceptibility Prediction</h1>

<h2>Description</h2>
Saint John, a coastal city in New Brunswick, faces significant flood risks due to its elevation profile and proximity to water bodies. This project predicts flood-prone areas using spatial data analysis, supporting data-driven planning and enhanced resilience for communities and infrastructure.  

### Features:  
- **Download and visualize spatial datasets**  
- **Combine dependent and independent variables**  
- **Use spatial overlays and raster analysis for modeling flood susceptibility**  
- **Incorporate elevation and land cover into prediction logic**  

The repository includes training logs, configuration files, required libraries and scripts to reproduce the results. 🚀  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Spatial operations and map visualizations using shapely, PIL, and rasterio</b>
- <b>2019 flood data from RNCan (real-world event data)</b> 
- <b>Digital Elevation Model (DEM)</b>
- <b>Forest Soil types</b>
- <b>Land cover</b>
- <b>Watershed boundaries</b>

<h2>Environments Used </h2>

- <b>Jupyter Notebook </b>

<h2>Program walk-through:</h2>

<br />
Install Libraries:  <br/>
<img src="https://imgur.com/aFeGOtd.png" height="80%" width="80%" alt="DL Model Training Steps"/>
<br />
<br />
Import Required Libraries: <br/>
<img src="https://imgur.com/4y441Ws.png" height="80%" width="80%" alt="DL Model Training Steps"/>
<br />
<br />
Downloading Shapefile:  <br/>
<img src="https://imgur.com/9kkEBe4.png" height="80%" width="80%" alt="DL Model Training Steps"/>
<br />
<br />
Downloading Watershed Data from ArcGIS API:  <br/>
<img src="https://imgur.com/GcG7eLp.png" height="80%" width="80%" alt="DL Model Training Steps"/>
<br />
<br />
Plotting the Map (Flood Prone Area In Saint John) on a World Basemap (Esri):  <br/>
<img src="https://imgur.com/J1xisD3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Plotting Saint John River Basin Watersheds:  <br/>
<img src="https://imgur.com/Ud8jB2b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Forest Soil Map of Study Area:  <br/>
<img src="https://imgur.com/zVUiLyx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Plotting DEM Aspect Map:  <br/>
<img src="https://imgur.com/W6ckg1o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Plotting Land Cover Map of Study Area:  <br/>
<img src="https://imgur.com/YjetZb9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Evaluating Different Algorithm Performances:  <br/>
<img src="https://imgur.com/8djRexA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Predicting Flood:  <br/>
<img src="https://imgur.com/PEzSNmF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
