cmake_minimum_required (VERSION 3.25)

project (CppProjectTemplate
	 LANGUAGES C CXX
	 VERSION 0.1.0)

# Overriding default variable
set(CMAKE_CXX_STANDARD          20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS       OFF)

# Setting variable names
set(LIBRARY_NAME Library)
set(EXECUTABLE_NAME app)

add_subdirectory(src)
add_subdirectory(app)




