# Notes on adding content to the game

## Maps
### Files to create
Maps are scenes stored under `/source/match/maps`. In order to make it available in the menu, you must add an entry to the appropriate array in `/source/match/MatchConstants.gd`.

Your best bet is to duplicate the `/source/match/Map.tscn` scene and move it into the correct folder to hold a map.

### Basic Data
Once the map scene is created, you need to add a few entities to it.
 - For each desired player, you need to drop a Marker3d under the SpawnPoints node
 - Under Resources, drag the ResourceA and ResourceB scenes into the map