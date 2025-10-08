Before running this script in the Google Earth Engine Code Editor, make sure to add the following Imports (shown in the top-left “Imports” panel in GEE).

Variable name	Type	Description
imageVisParam;	Type: Dictionary; Visualization parameters for SCATSAT Band-1 (used for map display).
imageVisParam2;	Type: Dictionary;	Visualization parameters for the second MODIS dataset (optional).
imageVisParam3;	Type: 	Dictionary;	Visualization parameters for the third MODIS dataset (optional).
snow;	Type: MultiPoint;	Training points representing snow-covered areas.
nonsnow;	Type: MultiPoint;Training points representing non-snow areas.
Modis_Snow;	Type: MultiPoint;MODIS validation points for snow pixels (MOD10A1 Daily).
Modis_nonsnow;	Type: MultiPoint;MODIS validation points for non-snow pixels (MOD10A1 Daily).
modisA2_snow;	Type: MultiPoint;MODIS validation points for snow pixels (MOD10A2 8-Day).
modisA2_nonsnow;	Type: MultiPoint;MODIS validation points for non-snow pixels (MOD10A2 8-Day).

How to add them:

1. Open script in the GEE Code Editor.
2. Click the “+” (Import) button or drag your assets from your Assets tab into the Imports panel.
3. Make sure each imported variable name matches exactly what the script expects (e.g., snow, nonsnow, Modis_Snow, etc.).
4. Save the script, then click Run.
