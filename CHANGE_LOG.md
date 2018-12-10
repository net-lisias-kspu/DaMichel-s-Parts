# DaMichel's Parts :: Change Log

* 2015-0222: 2 (DaMichel) for KSP 0.90
	+ This is a revision of the 2014 release. Now with better looking (i think) textures and mesh.
	+ RealFuels compatibiliy: configs are included.
	+ AJE compatiblity: The inlet has a configuration for AJE. I copied the config for the Sp+ rectangular inlet and made the inlet area larger. Not sure what i'm doing though.
	+ Swappable Tanks: If you have the Firespitter DLL and no RealFuels it will use it to give the parts swappable tanks. So you can chose between LF, LF+OX and MP variants.
	+ Usage of FerramAerospaceResearch is strongly recommended. The parts have some values for stock aerodynamic parameters but i have no idea if they are reasonable nor will i take the time to balance for stock. In contrast, FAR figures this stuff out automagically.
	+ ActiveTextureManager: I include a configuration which scaling in general and compression of the normal map. If you like a more aggressive configuration you should probably delete the cfg (damichel-fuselage-ATM.cfg).
	+ Relies on ModuleManager for the extra configurations, which is however not included. I haven't checked what happens if it is not already installed
* 2014-0418: 1.1 (DaMichel) for KSP 0.23
	+ For DMFuselages i went crazy and used insanely densely subdivided meshes with displacement maps to generate the normal maps from.
		- These highres meshes are not included because they are too big.
		- Everything else should be there.
	+ Don't be surprised to find Cinema4d files.
		- Though it is not ideal for game asset creation, it is my program of choice.
* 2014-0306: 1 (DaMichel) for KSP 0.23
	+ Spherical Tanks with 1.25 m base from 0.625 to 10 t
	+ "Flat" Fuselage pieces including two tanks in two sizes, an intake, an end piece and a tail boom for radial attachment.
	+ Radial Aerodynamic RTG, because i can. Has much lower drag in FAR than stock RTG due to not having attach nodes.
	+ New: Cargo Bay: 2.5 m diameter, relatively stock-like. Comes in heights of 1, 2 and 4 m for efficiency. Fits well to KWRocketry and B9 parts. The doors are designed to require less room for opening than a standard design made of a single door piece.