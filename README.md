# XP-Import
## Blender plugin to import X-plane object files into Blender 2.8+


### Another work in progress


These files are a mod of David Prue's original XP-Import for Blender 2.8

The original XP-Import could not be added onto any Blender over 2.79, each attempt created errors. 
So, I got to learn how Python3 and Blender worked together. They do pretty good, I think.

I really don't know how to create aircraft, or much of anything else, very well in Blender. So I repaired this importer to to be able to load it into Blender 2.8+, but I have not added much to the original, yet.

Currently, when object files are imported into Blender, you should move all of the newly imported objects into a new Collection, then import another obj file and move them objects into another new Collection. TODO: obj files should become a new Collection. 

I have loaded an entire X-Plane aircraft's many obj files into Blender 3.01 with this, and aircraft seemed to be displayed with the polys and textures positioned accurately, with functional editing.  


### If you are thinking that XP-Import can be used to edit an existing X-Plane aircraft:

This will not recreate names of the objects, assign animations, assign manipulators or datarefs. Practically, it will only import the objects poly's and apply their textures naming them OBJ-n's. 

It would be a lot of work to rename ALL of the objects, reassign ALL of the manipulators/datarefs and then rebuild ALL of the animations. 

# DO NOT VIOLATE LICENSE AGREEMENTS WITH THIS IMPORTER!



Click [here](https://github.com/EdmundStoner/XPImport.git) to download a zip of the XP-Importer. If you want to export a model from Blender into an obj file, you will need to install the most recent Xplane2Blender export plugin: https://github.com/X-Plane/XPlane2Blender

The zip file can be directly imported into Blender thru the preferences menu
