# SMBX-Overworld-Tilekit
OVERWORLD TILEKIT VERSION 1.0
Last updated March 5, 2020


---- CREDITS ----

The original Super Mario All-Stars graphics are copyright Nintendo, all rights reserved, etc.

Additional SMB3 ground tiles and border tiles by Sednaiur.  Please credit him if you use those.

SMB3-style cliffs, assorted edits and overall tileset arrangements by Rockythechao, credit is appreciated but not required as long as you do not claim these things as your own creations.


---- OVERVIEW AND USAGE ----

The Overworld Tilekit is a package of pre-made tilesets for the free Tiled map editor (http://www.mapeditor.org) that I put together to help streamline the process of making pre-rendered overworld maps.

Included is a sample/template .tmx file complete with the preloaded tilesets, SMB3 terrain autotiles (see the "Terrains" tab at the bottom of the "Tilesets" panel), and a pre-built example map ready to be exported as an image.

Once you've built the map and exported the image (or just exported the sample map), you'll need to split it up into chunks and replace world map tile graphics with these chunks, which you will then have to place in the editor.  As of the moment I'm writing this readme file, this is currently the easiest way to implement pre-rendererd world maps in SMBX.

For more information on how to use Tiled, you can find tutorials on Youtube, such as Gamefromscratch's series (https://www.youtube.com/watch?v=ZwaomOYGuYo&list=PL7BGDTz_CMf0eNuUes85xhJAqpZamNByz)


---- IMPORTANT NOTES ----

- This package is only meant to help with building the static terrain and does not include any animated tiles for elements like moving water, scenery, levels or paths.  Stuff like the waterfall tiles and "Path Planning" tileset are meant to help with planning the layout and distribution of these things in maps.  I recommend keeping these tiles on a separate layer and hiding that layer when exporting the map image, then placing them in the SMBX map editor.

- For simpler overworlds that only need the tiles that come pre-packaged with SMBX, I suggest simply building them entirely in the SMBX map editor.  This package will only really be more helpful for more complex world maps that would need a lot of additional tiles for things like cliff/ground seams.

- Please do not release expanded versions of this tilekit.  You are, however, free to release additional tilesets with other graphics for this package;  if you do so, I ask that you 
1) give credit to all contributors as would be expected with graphics packs and other resources,
2) clearly indicate that your tileset(s) are meant to be add-ons for this package, and 
3) link back to the main Overworld Tilekit SMBX forum thread for this package.
