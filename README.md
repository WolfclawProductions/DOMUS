# DOMUS User Guide
The Digital Open Modular Urban System- a Blender asset pack for archaeological reconstructions 
Installing and using Blender
This user guide assumes some very basic knowledge of Blender, mostly how to use the selection and transform tools for moving around the blocks. I recommend using [Blender Launcher](https://dotbow.github.io/Blender-Launcher/), a standalone launcher and version manager for Blender builds. 

Should you need it, the Blender Foundation provides a [Blender Fundamentals course](https://www.youtube.com/playlist?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6) . I recommend watching the first four videos in the playlist. DOMUS is intended to function as a sort of "digital lego", with users only needing to fit pieces into place. It will also be useful to familiarize yourself with the transform and scale tools in the tools bar, as precise numerical scaling and transforming is often the best approach for constructing buildings. 

The most important shortcuts you will need to know are: 
Shift + A - Add Object   Shift + D- Duplicate Object   Ctrl C/Ctrl V- Copy and Paste Objects   Select- Right Click   A- Select all

L- Select Current object   Middle Mouse Click- Pan   Middle Scroll- Zoom in/Out   Right Click (While Selected)- Move Points   R- Rotate

S- Scale   W- Specials menu   Number Pad- Change View   Backslash- Zoom to selected Object 

## Basic Building Blocks
The default wall sections (the blocks with no windows) provided in DOMUS are scaled to 9x1.84x10 feet. This number was loosely determined through observation from visits to Pompeii and Ostia Antica. The rest of the shapes vary in dimensions, but most of the blocks maintain an X width of 9 feet. This is what will most often be changed, as you can use a single block to represent a larger piece of wall. 

When moving the blocks, you can use the Snapping settings to align the blocks together. Testing has shown that these settings work best.
Transform Orientation: Global, Transform Pivot Point: Bounding Box, Snap: On (Blue), Snap to: Closest Edge OR Increment (try both and see which one you prefer).
You can use the floorplan of a house to recreate it. To import an "empty" image, you can user Shift + A, Image, Reference, and select an image file from your computer. 
If you need heights and references, you can import 3D models from Google maps using the process documented on the wiki. You can also just manually observe architectural features using Google Street view. 

There is an expanding selection of architectural features and Roman designs, with continuous research and modeling being done to expand the pack. 

## Textures
Each block has a series of up to three texture nodes. The "outside" blocks have nodes for controlling the color of the exterior trim (red by default), the color of the plastered wall, and the color of the brick or wooden trims. You can change the texture each node by selecting the dropdown menu. To see what each texture looks like, an array of spheres has been provided with each of the current textures (see above image). These spheres are also named after the texture to assist with your selection. Each piece has been individually UV-unwrapped, although you can make modifications by manually [UV Unwrapping](https://www.youtube.com/watch?v=Y7M-B6xnaEM&list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6&index=19) the pieces (no recommended for inexperienced Blender users. 
For those looking to set up their own textures, I recommend [Ambient CG](ambientcg.com/) and [Poly Haven](https://polyhaven.com) to source your textures, or you can set up textures using a map like this. All of the textures within the pack were sourced from the aforementioned sources, and are covered under a CC0 License.  Custom texturing is not currently within the skillset of the modeling team. 
