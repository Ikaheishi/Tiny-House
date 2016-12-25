Tiny House
====================
Initially started as a college homework assignment, Tiny House is a small game project and programming exercise of mine. The original was a very simple text adventure game based on a 2D array of rooms and finding one's way out of the mansion. This version is a complete rewrite from scratch to be a graphical mystery/adventure game, _possibly_ with some RPG elements.

Building
--------------------
Currently, the only dependencies are the C standard library (as always) and [Allegro](http://liballeg.org/).

The VS project is configured to look at the INCLUDE and LIB environment variables, so make sure that the paths to the Allegro headers and object files are in the respective variables.

To my knowledge, it should build fine on Linux (or any other Unix-like) systems—I haven't made it Windows-only and I very much intend to keep things working cross-platform. However, if you want any build automation, you will have to supply your own makefile for now. I'll eventually put a makefile together at some point. (Or perhaps someone else will first.)
