add_library(${LIBRARY_NAME} STATIC mylib.cc) # Creates a static library (Lib) from the source file src/mylib.cc
target_include_directories(${LIBRARY_NAME} PUBLIC "./")