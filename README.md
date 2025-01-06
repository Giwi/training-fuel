# Installation

    sudo ./warp10-standalone.sh bootstrap

https://www.prix-carburants.gouv.fr/rubrique/opendata/

- Draw WKT : https://clydedacruz.github.io/openstreetmap-wkt-playground/
- Draw/convert WKT/geoJson http://dev.openlayers.org/examples/vector-formats.html
- DRAW geoJSON : https://geojson.io

Usage: groovy convert.groovy PrixCarburants_xxx.xml

update limits

    sudo ./warp10-standalone.init start

# Data upload

    time curl --ciphers DEFAULT@SECLEVEL=1 -X POST  -H 'X-Warp10-Token: _UQ3kMixazvftKs19UMq2r4E69PJIZnmVlPb8FTbhaaV4TEnqUpWzD6PKPw.NJe3CkP7j.euyf7vix6rSAuBMV3q4AVUjtH52lS3bpB0EMQCdbJB2V9KE3ppG72FeGabEb3rKq9vaFVamXUGZqPFJF' https://warpcloud.senx.io/api/v0/update --data-binary @data.gts


# Practice

1. Gazole price in whatever during november 2018
2. Mean price by station
3. Global average
4. Mean of the last available diesel fuel prices in France
5. Find the cheapest fuel station near here
6. put_loc_in_attributes.mc2
7. Find the cheapest fuel station near here
8. Omit closed fuel stations
9. 10 km radial