add_executable (${EXECUTABLE_NAME} main.cc)
target_compile_options(${EXECUTABLE_NAME} PRIVATE -Wall -Werror -g)
target_link_libraries(${EXECUTABLE_NAME} PUBLIC ${LIBRARY_NAME})