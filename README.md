# TypesForBukkit Tools

This folder contains the tools I use to compile the TypesForBukkit package, which you can find [here](https://www.npmjs.com/package/typesforbukkit)

## DocRip
These tools allow me to rip the javadocs of the bukkit API from either the [Official Bukkit javadocs](https://hub.spigotmc.org/javadocs/bukkit/) or the achives on [HelpChat](https://helpch.at/docs/)
and then find any changes to the classes described in each file. Files that are completely new to the version are put in a seperate file. 

## Bukkit Collector
A not entirely feature complete web scraper for the javadocs. This makes collecting classes much quicker. It will collect the following information currently:
* Package name
* Class / Interface / Enum name
* Method names, return types, descriptions, and template for arguments with correct amount
* Enum members
* Will add a return statement for classes

Collected information will automatically be copied so the process of adding a new file is just: copy the name of the class, create new file, run the collector in browser, switch back to code editor, paste.

The script has a minified version that can be added as a bookmark for easy access.
