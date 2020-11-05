# Shades Map

This is a map for the text based multi user dungeon (MUD) game, Shades. Shades can be accessed through any popular MUD client or TELNET client by connecting to:
games.world.co.uk on port 23 For more information about the game, please visit the [Shades Website Here](http://games.world.co.uk/shades)

The map was generated using the website [trizbort.io](http://trizbort.io) and was exported into separate files for each area in JSON format.

## Area Separation
The map is divided into the following areas to improve readability
* Shades - the main map
  * Natural cavern
  * Winding path
  * Castle ground floor
  * Forrest around castle
  * Forrest outside Ruined city

* Castle - First Floor
  * First floor of castle
  * West Tower
  * East Tower

* Castle Garden

* Ruined City
  * Underground Lake

* Singing Pillars
  * Singing pillars
  * Obsidian cave
  * Rune room
  * Guards room

## Line Formatting
To make it easier to read the map, lines have been formatted as follows:
* Sold - normal path (N,S,E,W,NE,NW,SE,SW,U,D,I,O)
* Dashed - Leads to separate map file
* Dashed with label - Riddle or key required

Where required, notes are added to the line such as within the castle, leading to the dusty corridor there is a weight limit to enter.
Unless marked, the direction of the line is the compass direction you should walk in. Lines will include a note to indicate Up Down (dn) in or out where applicable.

# Contributing
To contribute to the map, please create a new issue with details of the area you intend to map so as to prevent cross-mapping. Then, create a pull request to submit changes. Pull requests will be merged once they have been verified.
Room name capitalisation should match those in game as when casing the where t spell, rooms sometimes appear different. I.E the treacherous swamp can be written as:
* treacherous swamp
* treacherous swamp.
* Treacherous Swamp
* Treacherous Swamp.

All files should be saved in the json format for consistency. When adding a new area, the readme file should be updated to show this new area, listing what it covers.
