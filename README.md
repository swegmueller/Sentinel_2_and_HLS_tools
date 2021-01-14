# Sentinel_2_and_HLS_tools
Tools for stacking and masking ESA's Sentinel-2 data and data from the Harmonized Landsat-Sentinel-2 dataset.

These Jupyter notebooks are being provided simply to help others in an informal way.  I've tried to keep them clean and well-commented, but don't hesitate to reach out if something is confusing. 

"Sentinel-2 Mask_Stack_revised" is a notebook that, as you might guess, masks and stacks S2 imagery. You need only download the imagery and point the system to the IMG_DATA folder.  WINDOWS USERS: you will need to change "/" to "\" for this to work for you.  I've tried to highlight where this needs done.  I only use select bands and mask everything except vegetation, but this can easily be changed for your needs.

"Take HLS data and write to GeoTif" does a similar thing, but with images from NASA's Harmonized Landsat-Sentinel-2 dataset (https://hls.gsfc.nasa.gov/). I wrote this bit of code a while back and borrowed heavily from colleagues. It works just fine for me, but its a bit more messy and you may choose to edit it a bit for your needs.  
