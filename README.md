# la-county-parks
Could refresh or add based on recently released county data http://egis3.lacounty.gov/dataportal/2016/07/07/park-needs-assessment/

There are also a lot of parks listed as nodes in OpenStreetMap that could be drawn or imported.

http://overpass-turbo.eu/s/i7M

<img width="787" alt="screen shot 2016-08-31 at 8 16 12 am" src="https://cloud.githubusercontent.com/assets/695934/18134445/45c29184-6f53-11e6-89db-372e0fec3cb0.png">

## Next steps
1. Compare OSM data to county data (using QGIS and Overpass turbo)
2. Possibly create a MapRoulette challenge asking for a trace of any node marked leisure=park
3. Possibly use the county's feature tilelayer to help define perimeters of park.

### Add L.A. County's feature tile layer to JOSM
1. In JOSM, go to Imagery > Imagery Preferences
2. Click the plus and "TMS" near the bottom right
3. Enter this URL `http://cache.gis.lacounty.gov/cache/rest/services/LACounty_Cache/LACounty_StreetMap/MapServer/tile/{zoom}/{y}/{x}`
4. Enter a name like `LA County features`

### Add L.A. County's feature tile layer to iD editor
1. Under the "Edit" mode in iD, click on the "Background settings" icon on the far right.
2. Select the magnifying glass next to "Custom"
3. Paste in this URL and hit "OK" `http://cache.gis.lacounty.gov/cache/rest/services/LACounty_Cache/LACounty_StreetMap/MapServer/tile/{zoom}/{y}/{x}`
![osm-tilelayer](https://cloud.githubusercontent.com/assets/695934/18134836/a71b9448-6f54-11e6-9e96-fae3df0e249c.gif)
