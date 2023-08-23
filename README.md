# longleaf-cones
Code associated with Cannon et al. (in review) Longleaf pine cones analysis

This code library contains items to calculate NDVI and daily precipitation from Brockway/Boyer Longleaf Pine cone sites

* **LLP_Brockway_sites**: Shapefile containing coordinates and descriptions of 12 Longleaf pine cone sites
* **pdsi--ppt-GEE**: Script to run in Google earth engine that utilizes the PRISM AN81d daily precipitation data to extract daily precipitation values back to 1981 for all sites. Script also uses GRIDMET data to extract 5-day PDSI values back to 1981 for study sites. Note: LLP_Brockway_sites file must be uploaded as assett to GEE.
* **winter-ndvi-GEE**: Script to run in Google earth engine that utilizes the LANDSAT 7 AND LANDSAT 8 imageryand estimates NDVI in the winter for all sites. Note: LLP_Brockway_sites file must be uploaded as assett to GEE.
