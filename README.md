# Blender SIRDS Extention

There are very little free and good programs for generating Autostereograms. Searching for one that is compatible with Linux is a treasure haunt. This patch for Blender will add a Compositor Node for the Blender Compositor to create very good SIRDS. It supports normal SIRDS with repeating pattern and also image projection SIRDS. There is a lot of room for improvements, but fiddeling with this patch is already a lot of fun.

Here is an example of what it can do with some setup:

![alt text](https://github.com/redweasel/blender-sirds-extention/blob/master/example_result.png?raw=true)

![alt text](https://github.com/redweasel/blender-sirds-extention/blob/master/example_setup.png?raw=true)

# Get it

To get it you have to compile blender yourself. Please refer to https://wiki.blender.org/wiki/Building_Blender for that.  
Then just apply this patch with a command like `git apply ./SIRDS.diff` depending on the place you put the diff.
