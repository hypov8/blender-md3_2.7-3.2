# .MD3 support for Blender

Blender addon for working with Quake 3 model format.

Can deal with animation (via the Shape Keys), textures and md3 tags (added as Empty objects).

More info on [BlenderWiki](https://archive.blender.org/wiki/index.php/Extensions:2.6/Py/Scripts/Import-Export/MD3/).

Used [this](http://www.icculus.org/homepages/phaethon/q3a/formats/md3format.html) format reference.

### tested working blender versions (import only)
- 2.7.9
- 2.8.0
- 2.9.2
- 3.2.1

### hypov8 changes
v0.4.4.1
- removed creating new scene for import. moved to collections (2.8)
- added node setup for skin
- added assemble of mesh to tags (option)
- blender 2.79 support (importer only done)
- multiple selected file import. implemented
- append md3 source names in tags (to help kingpin converter)

### todo:
- exporter. make backward compatable
- read .skin file
- fix wobble
- rigged models not animating. 
