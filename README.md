TextureUnpacker
========================

# Overview
Use this script to unpack **.png** sprites from the sprite atlas (providing a *.plist* file and a *.png* file) packed by [TexturePacker](http://www.codeandweb.com/texturepacker/).

# Requirements
  - [Python](http://www.python.org)
  - [Pillow (PIL fork)](https://github.com/python-pillow/Pillow) 

# Usage

For example, we have a pair of sprite files named: *Sprite.plist* and *Sprite.png* packed by [TexturePacker](http://www.codeandweb.com/texturepacker/).
Just run the following command in the folder congaing these files:
	
	python unpacker.py Sprite

and the script will generate a folder named **Sprite** containing all the small png files.