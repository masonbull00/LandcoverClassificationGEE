# NellieJuanClasificationGEE
The Google Earth Engine codes I created for creating training data and classifying landcover in the Nellie Juan Watershed.
These are numbered by the order they should be completed in. 
1: establish your training data and create an unsupervised classification to check your interpretation against the computer (This can be done once, or copied and used for each sensor you are using)
2: classify Landsat imagery with you input training data 

There are other optional codes in this repository as well.
Spectral Signature charting allows you to check your training data and classifications for continuity across satellites
Scan Line Correction accounts for scan line failure on Landsat 7 and should be added to codes using Landsat 7 data.

Reference training data for the Nellie Juan Watershed exist at these links:
Landsat 7 (2002): https://code.earthengine.google.com/?asset=projects/boise-state-bull-thesis-work/assets/NJ6Classes02_DEC16_2024
Landsat 5 (1986): https://code.earthengine.google.com/?asset=projects/boise-state-bull-thesis-work/assets/NJ6Classes86_DEC16_2024
Landsat 8 (2016): https://code.earthengine.google.com/?asset=projects/boise-state-bull-thesis-work/assets/NJ6Classes21_DEC16_2024

Here is a list of resources that are helpful for learning and navigating GEE:
Earth Engine Documentation, you'll mostly navigate through Client Libraries, but the Guides section has 
helpful tutorials and information about how Earth Engine Works: https://developers.google.com/earth-engine/apidocs
GIS Stack Exchange: https://gis.stackexchange.com/questions/tagged/google-earth-engine
Open Geo Blog. Lots of useful tutorials and workshops to help get your feet under you with GEE: https://mygeoblog.com/category/google-earth-engine/
End-To-End Earth Engine. This is a SpatialThoughts course that I referenced a lot when working on classification: https://courses.spatialthoughts.com/end-to-end-gee-supplement.html#introduction
