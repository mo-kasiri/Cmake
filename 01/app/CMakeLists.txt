add_executable (app main.cc)
target_compile_options(app PRIVATE -Wall -Werror -g)
target_link_libraries(app PUBLIC CustomLib)