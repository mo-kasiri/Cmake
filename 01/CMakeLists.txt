#0- Create Source and CMakeLists
#1- mkdir build && cd build
#2- cmake .. or cmake -S .. -B -> Generating the Build Files / Configure the project
#3- cmake --build .
#4- ./app -> run the executable

cmake_minimum_required (VERSION 3.25)

project (CppProjectTemplate
	 LANGUAGES C CXX
	 VERSION 0.1.0)

add_subdirectory(src)
add_subdirectory(app)




