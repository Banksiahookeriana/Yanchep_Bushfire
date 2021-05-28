# Yanchep_Bushfire


This repository is meant to generate some starter scripts and some basic spatial calculations around the Yanchep Bushfire

1)	Raster calcs by shapefiles 
a.	By each fire polygon
b.	By each polygon in the isochrones (the fire progression)
c.	By each soil type**
**note that there is a look-up table to merge into the attribute table and reduce to ~5 cover types**
OUTPUT:  typical metrics of a continuous variable (the RBR).  Also by each class (proportion or count).

2)	Push through a couple shapefiles to assign severity using the rf model you’ve built Ricky.  These are in a subfolder with the polygons and a CSV w details of each one.  I did include one 2015 polygon but drop that if you’re using sentinel.   I’ll run these myself through earth engine just to see what I get out.  
