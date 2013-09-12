myGeoJson
=========

Sous le compte fgarel,
 - il y a un repository github, qui s'appelle 
   - https://github.com/fgarel/myGeoJson
 - mais il y a aussi un 'gist', au sein de laquelle l'application
   - http://geojson.io/
   va créer automatiquement un gist map.geoson
   - https://gist.github.com/fgarel/

Doc
---
Les spécifications du format json sont ici
 - http://geojson.org/geojson-spec.html
 - https://github.com/topojson/topojson-specification/blob/master/README.md

ogr2ogr est capable de lire et ecrire du format json
 - http://www.gdal.org/ogr/drv_geojson.html

mais on peut aussi utiliser fiona
 - http://toblerity.org/fiona/manual.html

Exemple
-------
Conversion d'un geoson WGS84 en GeoJson LambCC46
ogr2ogr -f "GeoJSON" -s_srs EPSG:4326 -t_srs EPSG:3946 map3_3946.geojson map2.geojson


Pour passer de gist à repository
--------------------------------


Pour passer de repository à gist
--------------------------------



