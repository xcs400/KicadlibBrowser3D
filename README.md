# KicadlibBrowser3D
Online kicad lib browser for footprints and 3D models.

This is an unfinished work but it can be tested here: https://xcs400.github.io/KicadlibBrowser3D/

My goal is being able to see the Kicad(V5) footprint and 3D models available on the web (mainly from kicad official lib) but also from others sites without installing any tool. 

# todo

  -fix bugs (mainly in the .kicad_mod parser)

  -generate a dynamic list from the official .pretty folder and from others sites (here it is static from modellist.js)

  -setup a better browser

 
 
# credits 
The Vrml models and footprints are rendered using threejs/webgl : https://threejs.org/ 

The Vrml parser is from https://github.com/bartmcleod/VrmlParser based on Peg.js

The footprint viewver is a (partial) port from C++ to Javascript of the kicad_mod parser found in  https://github.com/compuphase/KiCad-Librarian

