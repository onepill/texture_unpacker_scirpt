texuture unpacker
========================

# Overview
this script use to unpack png files in the sprite(incluing a .plist file and a .png file) packed by [TexturePacker](http://www.codeandweb.com/texturepacker/)

# Requirements
  - [Python](http://www.python.org)
  - [PIL](http://www.pythonware.com/products/pil/)

# Usage

for example, we have a pair of sprite files named: Sprite.plist and Sprite.png packed by [TexturePacker](http://www.codeandweb.com/texturepacker/). just run the follwing command in the folder containg these files
	
	python unpacker.py Sprite

and the script will generate a folder named Sprite containing all the small png files.