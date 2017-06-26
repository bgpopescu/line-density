# How to calculate line density within a polygon

This is Jupyter notebook that shows step-by-step what the procedures are to calculate road density per district using Python and ArcGIS functions. The tutorial provides not only the code in order to run specific functions in ArcGIS but it also highlights conceptually what the required steps are in order to obtain a choropleth map showing density of roads within a district.  

I. Intro
I. Data sources
II. Table of Contents
III. Define your working directory
IV. Import ArcGIS Library
V. Examine Original geodatabases (optional)
- Original_euro_raster.gdb
- Original_ALB_adm.gdb
- Original_Roads.gdb

VI. Processing
I. Process: Create File GDB
II. Project shape files to WGS_1984_UTM_Zone_34N
III. Project elevation to WGS_1984_UTM_Zone_34N"
IV. Extracting by mask elevation
VII. Calculating Roads Motorway (highway)

I. Adding Unique District ID
II. Clip roads by districts
III. Add surface information
IV. Renaming the SLength field into the relevant variable name
V. Joining length of in meters of Road motoway to the District shape file
VI. Calculating area of districts taking elevation into consideration
VII. Density of Roads motoways (highway)
VIII. Step 5: Other types of roads
I. Primary Roads
II. Residential Roads
III. Secondary Roads
IV. Tertiary Roads
V. Track roads
VI. Trunk Roads
VII. Rail Lines

IX. Create jpegs of maps
X. Delete intermediary files from geodatabase (optional)
XI. Exporting the attribute tables to a txt file
