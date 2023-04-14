# UbiArt-DLC-Maker
Just Dance 2014 & 2015 has dlc support for inserting maps without modifying the base game. 

To get them working you would need other tools to pack the dlc data for specific platforms (Wii, Wii U, XBOX 360, PS3).

##How to use it.
* Make a 2014 or 2015 ipk and insert it to the root of the script.
* Open `input.json` and type in the mapname inside "maps" (don't forget about the jdversion).
* Run the tool and it will make a few files for the game to read the required data (atlascontainer.ckd, sgscontainer.ckd, dlcdescriptor.ckd, secure_fat.gf) and move your ipk to output.
* Packing dlc for specific platforms (*.wad, *.pkg) you're on your own.

