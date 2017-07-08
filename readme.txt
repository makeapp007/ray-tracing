Raytracing
I implement raytracing both sequentially and using CUDA.

Demos:
raytracing-demo.flv
result.png

The sequential version:
	Compile:
	pass compilation on mac(not sure on windows)
	in ray/ray/ 
		there exists CMakeLists.txt(if you know cmake)
		build/ there exists Makefile generated using cmake ..
			you can compile the program using make

	Run the program:
		./cg ../test.scene5

The cuda version:
Compile:
I use visual studio 2015 professional.
It should work well on this IDE as long as you set the library path correctly.

test.scenex
	different scenes

