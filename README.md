# Info
Real Steel is a high end modding toolkit for Dynasty Warriors 2, meant to replace my Dynasty Warriors 2 2.0 modding toolkit. It's not ready to release but i'll explain the future features.

# Steel Guider (meant to replace Visual Guider as the main Stage Editor to use)

The Steel Guider is Visual Guider overhauled with a new GUI. Panels can be moved around, you can hide the UI, etc. Like with Visual Guider it mods the battlefield data that determines who and where fights for side 1 and 2. Each stage has its map loaded, populated with all squads/forces on the map automatically, allows editing squad data (coordinates where squads spawn, leader id, guard id, parameters, etc), zooming in/out to adjust the display of the map, clicking a squad or their name in the list (which takes you directly to the squad so you don't have to manually find them) displays their squad data, morale bar toggle, guard toggle, etc. The Steel Guider does everything the Visual Guider can but has a way better design and still includes all the features visual guider had even the genetic algorithm.

# Unit Forge (unit editor)

This handles modding unit data which for DW2 involves name, model, motion/moveset, horse, color (uniform), etc. A new feature is Preview Image support, now you can see preview images of different units to help visually see what each color looks like for most models.

# Name Forge (string editor for unit names)

Handles modding the string names for units. This helps with having custom units made so that their name can be custom too.

# Bodyguard Forge

This tool handles modding player bodyguards. Ever noticed how player bodyguards can only ever have sword movesets no matter how much they progress for ranks/class? With Bodyguard Forge you can mod how your bodyguards' progress. That means you can have bodyguards with different movesets (sword, spear, pike glaive, etc), models, etc. Image 12 is an example of a mod made by Bodyguard Forge.

# Item Calibration Bay

Handles modding the item data.

# Map Editor

This is very different from Steel Guider. Stage Data (what the Stage Editor mods) involves what is basically battlefield data, like who fights on the stage. The Map Editor will mod the literal maps. That'll include objects on the map (gates, walls, castles, boxes, towers, flags, breakable boxes/vases, etc), collision data so objects have proper physics, terrain data (the terrain itself such as hills, land, etc), and other things. The end result will be allowing you to create entirely custom and new maps. This is a work in progress but it has been tested by me and i've even made videos of playing on a custom Hu Lao Gate map where I moved where Si Shui Gate is actually located. The videos showing this are in the musou warriors discord server.

Map Editor is going to be redesigned with a Steel theme but i included a sneak peak image of what the prototype originally looked like (image 9). Images 10 and 11 show examples of modding the map, image 10 shows Si Shui Gate positioned further north while image 11 shows the breakable boxes/vases that originally start near one of the respawn gates near Yuan Shao being placed near a tree further south.

You will not be able to import custom models from other games. DW2 uses a custom model format, specifically a model container (.ps2 specifically). I would rather focus my time on making a full fledged map editor than spend tons of time dealing with model conversion work (since i'd have to implement logic for converting obj, fbx, etc to .ps2).

# Future Plans

I hope to make an Event Editor, this would allow custom events to be made and open a lot of potential for scripting possibly. There are other tools indevelopment for DW2 modding during my free time but my biggest focus is getting the map editor finished. 
