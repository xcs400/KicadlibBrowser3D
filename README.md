# KicadlibBrowser3D
Online kicad lib browser for footprints and 3D models.

This is an unfinished work but it can be tested here : https://xcs400.github.io/KicadlibBrowser3D/

todo: 
 -fix bugs (mainly in the .kicad_mod parser)
 -generate a dynamic list from the official .pretty folder (here it is static from modellist.js)
 -add external public path
 -setup a better browser
 ...
 
 
credit: 
The Vrml models and footprints are rendered using threejs/webgl : https://threejs.org/ 
The Vrml parser is from https://github.com/bartmcleod/VrmlParser based on Peg.js
The footprint viewver is a (partial) port from C++ to Javascript of the kicad_mod parser found in  https://github.com/compuphase/KiCad-Librarian


