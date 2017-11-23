# Blender-RSD-Plugin
A Blender Plug-in for Exporting Models in PlayStation SDK RSD Format.

This plug-in supports exporting flat shaded, gouraud shaded and texture mapped tris and quads in PlayStation SDK compatble RSD, PLY and MAT file formats. Semi-transparency attributes can also be set but per-polygon semi-transparency is currently not supported.

This plug-in is an improvemnt over the original Blender RSD export plug-in found in the psxdev forums. This version fixes the reocurring bug where texture coordinates for quads are sometimes not exported correctly as well as performing a lot faster than the original plug-in.

Should be compatible in Blender 2.69 and later (recently tested on 2.78c).

## Installation
Simply install the plug-in by using the Install from File option in the Add-ons tab in Blender User Preferences.

## Changelog
**Version 2.0.0**
* Initial github release.