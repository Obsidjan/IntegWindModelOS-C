# IntegWindModelOS-C
Pulling together an end-to-end model for wind-related physical risk, as a component of OS-C's physical risk models library.

The hurricane dynamics model can be run as follows:
1. Create a directory for a set of related model runs with subdirectories for input and output files (as described below).
2. Create a site file (sites.csv) with geographic coordinates for one or more study sites.
3. Download or create geographic and political boundary shapefiles for the desired geographic region. The coordinate system should be latitude/longitude (degrees). Rename these files so the first name of each file is "boundaries".
4. Create a land-water file (land_water.tif) for the region.
5. Create a parameter file (parameters.csv) with parameters for all hurricanes and (optionally) for particular hurricanes.
6. Create an input hurricane track file (input_tracks.csv) for the geographic region. If desired, this file can be created directly from HURDAT2.
7. Run the model to create site and regional estimates. Use the plot functions to view model results.