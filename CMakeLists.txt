cmake_minimum_required (VERSION 2.6)

project (mytest)

add_executable (${PROJECT_NAME} test.cxx)

install (TARGETS ${PROJECT_NAME} DESTINATION bin)
