# supportyourlocalFC
Map of the United Kingdom and Ireland divided up by distance to the nearest football club.
Seeing as some football fans have an obsession with the 'Support your local club' attitude, I decided to see which club would be the biggest if everyone supported their local club.
Map shows clubs from: English Tiers 1-6, Scottish Tiers 1 and 2, Northern Ireland Tier 1 and Ireland Tier 1.

Process:
Choosing clubs. English Tiers 1-6 are all decently large clubs, and the 6th tier is somewhat comparable to the second tiers of other countries
Cymru Premier is a very small league, so I used the Welsh EFL clubs only.
Scotland and Ireland received two tiers, the second tier has decently sized clubs.
Northern Irish league is quite small, but otherwise they 
Extracting location data from Wikidata. This was done because no other preexisting file had the stadium locations I needed.
Added the csv file and made Voronoi polygons - Each region is bounded by a line equidistant to another point.
Added population raster data and calculated population for each polygon
Used qgis2web
