Following libraries need to be installed and linked to run visualizations.
glew
freeglut
To use in Visual Studio :
* Build > Project Properties > C/C++ > Additional Include Libraries > Add path to glew and freeglut include directories
* Build > Project Properties > Linker > Additional Dependencies > Add "freeglut.lib", "glew32.lib"
* Build > Project Properties > Linker > General > Additional Library Directories > Add path to glew and freeglut lib directories
