# GEE_Deforestation

This script was written by Olivier Hacking for 510 global.

It can be easily adapted to encompass different areas instead of the Karonga and Chitipa Districts in Malawi.


These variables are user account-specific and will provide errors if you run the script:

1. lakemalawi
2. districts
3. flowacc_defo
4. flowacc_bare

Variables 1 and 2 are provided in this repository in shp format:
1: malawi_lake.zip
2: malawi_district_boundaries.zip

Variables 3 and 4 are both calculated in ArcGIS Pro, you can do this too by running the export functions
in the GEE script in Chapter: [6] Exporting and using those as inputs for the flow accumulation tool
in ArcGIS Pro, or other software.

flowacc_defo: flow accumulation with deforestation weight raster
flowacc_bare: flow accumulation raster

Good luck and have fun with the script =)
