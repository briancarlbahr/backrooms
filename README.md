backrooms

A simple example backrooms map and biosuit version of mr fixit for Cube 2 Sauerbraten.

briancarlbahr.com 2022

https://github.com/briancarlbahr/backrooms

Artwork CC-BY-SA 3.0

Code GPL 2.1

(Some files by other authors may be covered by different license)



copy contents of directory "packages" into ~/.sauerbraten/packages/

in the game hit "~" to access the console and type "map backrooms" to load the map

this heavily modified mr_fixit.blend (by geartrooper) file will replace your "mr fixit" model.   To restore the old model simply delete the mrfixit directory form this mod.



If you want to edit the "biosuit" model use blender verion 2.72 and the included pythons script io_export_md5-263.py

After exporting the md5mesh add "	// meshes: Body" the files as shown below:

----------------------------------------
...

mesh {
	// meshes: Body

	shader "Body"

	numverts 1476
	vert 0 ( 0.581062 0.530181 ) 0 2
	vert 1 ( 0.606974 0.490616 ) 2 2

...
----------------------------------------

