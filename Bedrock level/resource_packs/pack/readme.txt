# Foxy's Markers [Experimental]
# Created: 22/05/2021 [dd/mm/YYYY]
# Version: 1.0.2

# Made for MC Bedrock Edition 1.16.220+
# For more info visit https://www.foxynotail.com


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
	
e. Biome Detection
	- The code required to detect which biome the armor stand in is still locked behind Experimental mode.
	- This means you'll need the non-experimental version of the pack for realms / servers and non-experimental worlds.
	


How to use:=
============
Give an armor stand any banner and then change the pose.
Currently there are 12 available settings. The first and last armor stand poses are not currently used.

This experimental version requires the Holiday Creator Features experimental toggle to be activated in your world settings.



Features:=
==========
Pose 1:  Spawn Spheres 
		 - 24 Block Radius (Green) & 54 Block Radius (Red)
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
		- If using the experimental version of the pack the coords will be switched when inside the nether, so the Nether coords (Pose 11) will be correct and the Overworld Coords (Pose 10) will be multiplied by 8
		- If not using experimental verison of the pack the nether coords (Pose 11) will be incorrect when used inside The Nether.
		
Pose 12: Biomes [Experimental]
		- Shows which biome the armor stand is stood in
		- If the biome is not found it will show Overworld / Nether depending on the dimension.


Special Thanks:=
================
Inspired by RavinMadHatter's Chunk Borders Pack: https://github.com/RavinMaddHatter/Bedrock-Chunk-Boarders-Pack