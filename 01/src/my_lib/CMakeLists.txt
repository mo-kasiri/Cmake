add_library(CustomLib STATIC mylib.cc) # Creates a static library (Lib) from the source file src/mylib.cc
target_include_directories(CustomLib PUBLIC "./")