
super quick and simple tool that will translate
kenny spritesheets to a usage json atlas

See here for his main site
http://www.kenney.nl/

How to use: 
python produce-kenny-atlas.py -i XMLFILE -p PNGFILE 
- the xml file is the spritesheet xml file that kenny provides in the spritesheet directory
- the png file is the matching png file for the xml file (the spritesheet)

dependencies:
- python pillow the friendly PIL fork https://python-pillow.github.io/
	(PIL should work too it is just used to get width/height of the image)

