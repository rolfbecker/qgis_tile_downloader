# QGIS Plugin `qgis_tile_downloader`

https://www.opengeodata.nrw.de/produkte/geobasis/hm/dgm1_xyz/dgm1_xyz/

https://www.bezreg-koeln.nrw.de/brk_internet/geobasis/hoehenmodelle/digitale_gelaendemodelle/index.html

## TO INSTALL THE PLUGIN:

* Open the QGIS folder in appdata (type %appdata% on your Windows search bar and it should show up), QGIS3, profiles, default, python, plugins;
* Copy the folder containing this repository to that path mentioned;
* Open QGIS, go to plugin > manage and install plugins;
* In the installed plugins tab, check the box corresponding to this plugin;
* Ready to go! If it doesn't show up in your plugin tab, restart the software.

## Usage

In the data subfolder you find the geopackage file `NRW_DTM_NRW_EPSG_25832_Tiles_BB.gpkg`. It is a vector layer containing the 35860 NRW wide bounding boxes representing the DTM tiles' location and extent. Add this vector layer to your QGIS project. The attribute table of the layer consists the names of the associated XYZ files in the DTM repository. 



