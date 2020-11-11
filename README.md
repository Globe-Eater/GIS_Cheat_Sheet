# Setup tips:
Connect new folder in ArcCatalog.

### Enable Spatial Analysis Extension for Raster analysis:
<ol>
<li> Click Customize. </li>
<li> Select Extensions. </li>
<li> Check Spatial Analyst. </i>
</ol>

# Setting Enviroment:
<ol>
<li> Right Click toolbox button. </li>
<li> Click set enviroment. </li>
<li> Set folder to your project folder. </li>
</ol>

# Vector Tools:
<ul>
<li><b>Clip (Analysis Tools)/<b> Removes all features outside the selected area and combines layers within the section.</li>
  <li><b>Merge (   </b></li>
<li><b>Intersect ( </b> </li>
<li><b>Dissolve ( </b> </li>
<li><b>Buffer ( </b> </li>
<li><b>Union ( </b> Combines all features into one.</li>
</ul>

# Raster tools:
<ul>
<li><b>Extract by Mask (Extraction):</b> used for combining raster data with a vector layer (ex. a county combining with a DEM) </li>
<li><b>Reclassify </b> Used to change range of values in a raster dataset. </li>
<li><b>Create Mosaic Dataset (Data Management Tools)</b> creates a empty reaster file. </li> Lab4 page 4.
<li><b>Add Rasters to Mosic Dataset (Data Management Tools)</b> Will fill empty raster files. </li> Lab4 page 4.
<li><b>Calculate Statistics (Data Management Tools)</b> Note this may not appear in the catalog or table of contents. Close and reopen arcmap. Lab4 page 5. 
<li><b>Merge Mosaic Dataset Items (Data Managment Tools) </b> Merges two rasters to make their values aline. </li>
<li><b>Slope (Spatial Analyst Tools) </b> Calculates the inclination of a planar feature from DEM values. HOW STEEP IS IT? </li> Lab4 page 9
<li><b>Aspect (Spatial Analyst Tools) </b> Visiually shows the direction the ground is facing. ie the north side of the mountian will be red for 000 degrees. </li>
<li><b>Hillshade (Spatial Analyst Tools) </b> Casts light on a set angle to help show the relief of the terrian. </li> Lab 4 
</ul>

# Projections
<ul>
<li><b>Define Projection (Data Managment):</b> On the fly - does not perminately change projection. </li>
<li><b>Project </b> Transforms the layer perminately. </li>
</ul>

# Geodatabase:
## Creation
<ol>
<li> In Catalog, right click the folder your project is in. </li>
<il> Select create new Geodatabase. </li>
<li> Fill in correct projection to apply and other crap. </li>
</ol>

## Create Feature Datasets: You would do this if if you needed to organize a lot of layers
<ol>
<li> Right click the geodatabase. </li>
<li> Select Feature Dataset. </li>
<li> Set coordinate system. </li>
<li> Tolerances - X, Y set 0.1, Z set to 0.1, M set to 0.1. </li>
</ol>

## Import data:
<ol>
<li> Right click a feature dataset if working with normal vector data. </li>
<li> Select import. </li>
<li> Feature Class (multiple)... </li>
<li> Input paths to files and run. </li>
</ol>


# WaterShed analysis stuff:
<ul>
<li><b>Sink (Spatial Analyst)</b> Changes flat areas into lakes. </li>
<li><b>Fill (Spatial Analyst)</b> will correct all sinks by forcing them to drain. </li>
<li><b>Flow Direction (Spatial Analyst)</b> Will show flow direction </li>
<li><b>Flow Acculmulation (Spatial Analyst)</b> LAKES and RIVERS.</li>
</ul>

# Other:
## Calculate Geometry:
<ol>
<li> In the attribute table create a new field.</li>
<li> Right click the top of the field. </li>
<li> Select calculate Geometry. </li>
<li> Specifiy conversion to new type. </li>
</ol>

## Field Calculator:
<ol>
<li> Right click a field in the attribute table.</li>
<li> Enter function and pray. </li>
</ol>

## Joins
<ol>
<li> Right click on a layer. </li>
<li> Select Joins and relates </li>
<li> Select Join... </li>
<li> Specify two input fields to join on. They need to have the EXACT same information. Order does not matter.</li>
</ol>

## Ruler:
<ol>
<li> Top Bar, find a yellow ruler and left click. </li>
<li> Right click on map to speifiy distance units. </li>
<li> Left click on start point to measure. </li>
<li> Left click again to drop another point or to stop. </li>
</ol> 

## Map Layout:
<b> THE TINY BUTTON IN THE BOTTOM LEFT HAND CORNER THAT YOU WOULD NEVER EVER KNOW WAS THERE UNLESS SOMEONE TOLD YOU. </b>

## Portrait vs Landscape
<b> While in the map layout mode, select file, select Page and Print Setup, Orientation will be halfway down the new window. </b>

## "Cartographiclly correct" map elements:
<ol>
<li>Scale Bar</li>
<li>North Arrow </li>
<li>Legend</li>
<li>Title</li>
<li>Metadata Information (date, author's name, source of data). </li>
<li>Neatline</li>
</ol>

## Transparency:
<ol>
<li>Open the properties of the layer in question by right clicking it and selecting properties. </li>
<li>Select the Display Tab, towards the bottom you will find transparency. </li>
</ol>


