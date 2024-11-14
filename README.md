# Ultimaker-Original-CNC
all the code and 3d files that i used in converting my ultimaker original to a cnc. I am aware of the grbl software out there but sadly the Ultimaker uses an Arduino mega board which is not compatibel with grbl (there is a Arduino mega branch but that looked outdated and i couldn't get the arduino to respond after instalation)

Currently the code takes an array of point as input. this array is generated on https://spotify.github.io/coordinator/ .I am not planning on implementing g-code since it is for personal use only. The web interface currently only contains the html and css because i have not gotten to writing the javascript.   

The next step in this project is to upgrade the hardware elements since the steppermotors aren't quite strong enough to cut through wood.
