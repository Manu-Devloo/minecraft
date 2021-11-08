# Foxy's Armor Stands+ & Markers Combo [Experimental]
# Created: 03/06/2021
# Version: 1.0.0
# Made for MC Bedrock Edition 1.17
# For more info visit https://www.foxynotail.com

Notes:
Chunk Borders & Spawn Spheres won't show if the armor stand has been scaled.
Chunk Borders won't show if the armor stand is not stood in a cardinal direction (Rotated on the Y axis)

This experimental version requires the Holiday Creator Features experimental toggle to be activated in your world settings.


ARMOR STANDS +
##################
HOW TO USE
==========
This pack overwrites the default armor stand in Minecraft Bedrock Edition.
Please note that this pack WILL need updating for future Minecraft Bedrock Versions.
Please download the updated version from foxynotail.com when it is available.

Shift (Crouch) and click with different dyes to change the look, position and rotation of the armor stand.

VISUAL
======
Black Dye -> Toggle Geometry
#:		Size		Baseplate		Arms
1: 		Normal		On				Off
2: 		Normal		On 				On	
3: 		Normal		Off				On
4: 		Normal		Off 			Off
5: 		Medium		On				On
6:	 	Medium		On 				On
7:	 	Medium		Off				Off
8:	 	Medium		Off 			On
9: 		Small		On				On
10:	 	Small		On 				Off
11:	 	Small		Off				On
12:	 	Small		Off 			On
13:		Large		On				Off
14:	 	Large		On 				On
15:	 	Large		Off				On
16:	 	Large		Off 			Off

GRAVITY
=======
Gray Dye -> Toggle Gravity

VISIBILITY
==========
White Dye -> Toggle Invisibility

ROTATE Y
========
Blue Dye -> Clockwise
Green Dye -> AntiClockwise

ROTATE X&Z
============
Yellow Dye => Rotate by 15 degrees (X)
Light Blue Dye => Rotate by 15 degrees (Y)

POSITION
========
Orange Dye 	-> +X
Brown Dye	-> -X		
Pink Dye	-> +Y
Purple Dye	-> -Y		
Lime Dye	-> +Z
Cyan Dye	-> -Z

SIT
===
Light Gray Dye -> Sits the armorstand down

LOCK
====
Magenta Dye -> Toggle Locked / Unlocked
Note: Locking does not prevent players from breaking the armor stands. It also does not turn gravity off. Use the Gray dye for that first.

##################################
##################################

MARKERS
#######
Armor stands with banners will show a variety of useful info when posed.


Limitations:=
=============
a. As this is a resource pack and can't access deeper data like an addon/behavior pack, there is limited information that this can access.
	- It cannot detect light levels or be adjusted for game difficulty / simulation distance.
	
b. Entity Render Distance
	- On bedrock, entities cannot be seen beyond 70 blocks on most devices.
	- This means the despawn sphere is only just in view when you're outside it.
	- There are no options to increase this distance so there is no point in making larger despawn spheres as you won't be able to see them.
	
c. FPS
	- The FPS meter is very fast and looks a little blurry
	- It's not possible to slow this down with just the resource pack sadly.
	
d. Measure Distance
	- Again, due to entities not being visible passed 70 blocks, the measure will only work up to 70 blocks away from the armor stand.
	- If you need to measure longer distances than this, use multiple armor stands.
	

How to use:=
============
Give an armor stand any banner and then change the pose.
Currently there are 11 available settings. The first and last two armor stand poses are not currently used.


Features:=
==========
Pose 1:  Spawn Spheres 
		 - 24 Block Radius (Green) & 44 Block Radius (Red)
		 - 44 Radius is the despawn radius with a 4 chunk Simulation Distance
		 
Pose 2:  Chunk Borders (1 chunk)
		 - Chunk border is aligned to the chunk that the armor stand is inside of
		 - Does not work if the armor stand is placed on a diagnal orientation
		 
Pose 3:  Chunk Borders (3x3 chunks)
		 - Same as above but shows a grid of 3 x 3 chunks around the armor stand
		 
Pose 4:  Chunk Borders (5x5 chunks)
		 - Same as above but shows a grid of 5 x 5 chunks around the armor stand
		 
Pose 5:  Compass
		- No matter which way the armor stand is facing, the compass will always point north
	
Pose 6:  Measure Distance
		- Great for measuring straight lines, heights and making circles!
		- Shows the distance to the player (camera)
		- Using the third person camera will affect the distance as this measures the distance from the armor stand to the camera.
		- It will measure in all axis and directions

Pose 7:  Day
		- Shows the current in game day
		
Pose 8:  Time of Day
		- Shows the time of day (in ticks) from 0 - 24000
		
Pose 9:  FPS
		- Shows your current Frames Per Second

Pose 10: COORDS
		- Shows the coordinates of where the armor stand is placed
		- Limited to 99999 blocks in each direction
		
Pose 11: NETHER COORDS
		- Shows the corresponding nether coordinates of where the armor stand is placed (Overworld X & Z divided by 8)
		- Limited to 99999 blocks in each direction		
		- This pose will show incorrect coordinates when inside The Nether dimension
		
Pose 12: Biomes [Experimental]
		- Shows which biome the armor stand is stood in
		- If the biome is not found it will show Overworld / Nether depending on the dimension.