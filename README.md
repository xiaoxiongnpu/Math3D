# Math3D

**Math3D** is a portable high-performance 3D math library from [Ara3D](https://ara3d.com) in pure C#. 
Math3D was originally forked from [MonoGame](https://github.com/MonoGame/MonoGame) an open-source version of XNA, and modified to use the core 
classes provided in `System.Numerics`. 

## Related Libraries 

* [Math.NET Numerics](https://github.com/mathnet/mathnet-numerics)
* [Geometry3Sharp](https://github.com/gradientspace/geometry3Sharp)
* [MonoGame](https://github.com/MonoGame/MonoGame)
* [FNA-XNA](https://github.com/FNA-XNA/FNA/tree/master/src)
* [Xenko](https://github.com/xenko3d/xenko/blob/master/sources/core/Xenko.Core.Mathematics)

## Todo 

* Creating double precision versions of many of the data structures and algorithms
* Investigate integrating code from [Geometry3Sharp](https://github.com/gradientspace/geometry3Sharp) by Ryan Schmidt.
* Some of the classes have really redundant code that can be auto-generated by TT files
	* ToString
	* GetHashCode
	* Equals 
	* Add / Subtract 
	* Merge 
	* Intersects 
	* Serialization code. 
* I have the feeling that there are some possibilities for intersection interfaces
