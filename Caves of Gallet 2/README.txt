Original (Cavernas) by Adam Saltsman on itch.io
Improved by Kaizar Nike

Intended for public domain use, commercial rights free to use. (As I originally found it.)

Intended for Godot import on version 3.X. If issues or concerns, leave a comment on itch!

For use in your project: Copy Assets folder and LevelTemplate.tres into your project. Create a TileMap (2D) node, and load the LevelTemplate as it's Tile Set. Set the cell size to 8x8 pixels and make sure the cog_tileset_version2.png import is not set to filter for most pixel clarity.

I saw my NVIDIA card have trouble with lots of these tiles, try setting Quadrant Size to 1 and Pixel Snap on.

Q: How to make my own tiles?

A: Use the tileset png as reference (grass is partially done.) Try programs like Tilesetter. For a side-scrolling platformer- a 3x3 minimal bitmask for your autotile covers most things. For all uses that means a lotta tiles! I find there's a minimum of 14 needed to get the most basic rectangles (must be at least two thick.) In the picture (cog_tileset_version2.png) you will see annoying white and gray spots, these are for debugging. If you see these while painting with autotiles, you need an extra tile there.

Q: Can I make a game with this project as base?

A: Sure!

Q: Where can I go for even more help?

A: Try Godot's discord!