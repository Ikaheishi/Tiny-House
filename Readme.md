Tiny House
====================
Initially started as a college homework assignment, Tiny House is a small game project and programming exercise of mine. The original was a very simple text adventure game based on a 2D array of rooms and finding one's way out of the mansion. This version is a complete rewrite from scratch to be a graphical mystery/adventure game, _possibly_ with some RPG elements.


Dependencies
--------------------
Currently, the only dependencies are the C standard library (as always) and [Allegro](http://liballeg.org/).


Building
--------------------
The VS project is configured to look at the ``INCLUDE`` and ``LIB`` environment variables, so make sure that the paths to the Allegro headers and object files are in the respective variables.

To my knowledge, it should build fine on Linux (or any other Unix-like) systems—I haven't made written anything Windows specific and I very much intend to keep things working cross-platform. However, if you want any build automation, you will have to supply your own makefile for now. I'll eventually put a makefile together at some point. (Or perhaps someone else will first.)

License & Disclaimer
--------------------
Copyright © 2016-2017 Ikaheishi

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

**This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.**  See the GNU General Public License for more details.

_You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>._
