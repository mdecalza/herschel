# [DoomMake Project]

by YOUR NAME/TEAM HERE (C) YEAR

## What This Is

This is a project created by DoomMake. This section should include information about it.


## What You Need To Do First (Yes, YOU, the person who made this project)

This project may need some tweaks before you make project this available for others to
clone and build. For example, you may not need everything generated in the make script 
or in the merge scripts. For more information, see the following files in your DoomTools
directory:

	docs/WadMerge Help.txt
	docs/RookScript Quick Guide.txt
	docs/WadScript Help.txt
	docs/DoomMake Help.txt


Also, fill out the project file name in `doommake.project.properties`.


## Generated by the Project

Some directories/files in this project are ignored (or *should* be ignored) by repository "ignore" files:

	/build               Build directory.
	/dist                Distributables directory.
	doommake.properties  Project property override file.


## Before You Build This Project

This project may need some local properties filled in by whoever clones this project.
Make a `doommake.properties` file and look at the properties in `PROPS.txt` for the
modifiable settings for this project. The `doommake.properties` file that you create should
NOT BE CHECKED IN TO YOUR REPOSITORY!


## To Build This Project


This project requires the [DoomTools](https://github.com/MTrop/DoomTools) toolchain for
building it. Clone this project to a new folder and type:

	doommake init


...In order to ensure everything has been prepped correctly (some directories or files
may need extracting, downloading, or copying).

To clean the build folder, type:

	doommake clean


To both initialize and build this project and its distributable archive:

	doommake


To build the DeHackEd patch from DECOHack source:

	doommake patch


To convert raw assets to Doom assets:

	doommake convert


To build the assets WAD:

	doommake assets


To build just the maps WAD:

	doommake maps


To extract only the textures used by maps to a separate WAD file (if any):

	doommake maptextures


To run this project (after setting the correct properties):

	doommake run


To build all components:

	doommake all


To build the full release:

	doommake release

