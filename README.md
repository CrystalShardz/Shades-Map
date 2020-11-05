# Shades Map

This is a map for the text based multi user dungeon (MUD) game, Shades. Shades can be accessed through any popular MUD client or TELNET client by connecting to:
games.world.co.uk on port 23 For more information about the game, please visit the [Shades Website Here](http://games.world.co.uk/shades)

The map was generated using the website [trizbort.io](http://trizbort.io) and was exported into separate files for each area in JSON format.

### How to use
1. Download a copy of this git repository to your computer
2. Visit the trizbort.io app website - http://trizbort.io/app/index.html
3. Expand the menu by clicking the three horizontal bars in the top left corner of the web page
4. Under File select Load map
5. Browse to where you downloaded the repository files to and select the area file you wish to view

## Area Separation
The map is divided into the following areas to improve readability (this section is being updated as new areas are added)
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

## Items & NPC's
Items shown on the map always spawn in the locations they are marked at. Other items are not marked on the map currently. Items marked are displayed to the lower-right of the box they apply to. If you are unsure which room an item belongs to in a densely populated area of the map, you can click the room and select Objects from the right panel to view more details.

NPC path's are not currently marked on the map.

# Contributing
To contribute to the map, please create a new issue with details of the area (remembering to add the tag Exploration) you intend to map so as to prevent cross-mapping. Then, create a pull request to submit changes. Pull requests will be merged once they have been verified.
Room name capitalisation should match those in game as when casting the where t spell, rooms sometimes appear different. I.E the treacherous swamp can be written as:
* treacherous swamp
* treacherous swamp.
* Treacherous Swamp
* Treacherous Swamp.

All files should be saved in the json format for consistency. When adding a new area, the readme file should be updated to show this new area, listing notable sections that it contains.

When multiple exits exist for the same room (I.E you can go both NORTH and UP to reach the next room) only one exit should be documented to keep the map legible. You are free to choose which however please pick the exit that makes most sense. For example, it makes more sense to go UP a set of stairs rather than NORTH. Especially as the reverse of this would be DOWN rather than SOUTH.
If diagonal exits (NE,NW,SE,SW) end up in the same room as a horizontal exit (N,S,E,W) then these can be omitted.
