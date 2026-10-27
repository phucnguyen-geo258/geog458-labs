## Lab 3 Independent Map – Seattle Soccer Fields

For my independent map, I decided to focus on soccer fields in Seattle and compare their different surface types. I downloaded the Soccer Fields dataset from Seattle GeoData as a GeoJSON file. The dataset includes information such as field names, addresses, surface types, and whether the fields have lights.

First, I imported the GeoJSON file into QGIS and changed the symbology to Categorized using the `E_SURFACE` field. I used green for grass fields, orange for synthetic fields, and gray for other or unknown surfaces. After that, I used QMetaTiles to export the styled soccer fields into PNG raster tiles with zoom levels from 8 to 12.

Next, I created a second basemap in Mapbox Studio and connected it to QGIS using the WMTS URL. I also exported this basemap into a separate folder using QMetaTiles. This gave me two different tile sets, one for the basemap and another for the soccer field layer.

After finishing the QGIS part, I used MapLibre GL JS in VS Code to combine both raster layers with the original GeoJSON data. I added checkboxes so users can turn the soccer field raster and interactive points on or off. I also added a legend and clickable points that show each field's name, address, surface type, lighting information, and division.

The main purpose of my map is to help users see where soccer fields are located in Seattle and understand the differences between grass and synthetic surfaces. This lab helped me understand how to export map tiles from QGIS and combine raster and vector data in an interactive web map.