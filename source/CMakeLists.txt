add_executable(helloworld helloworld.cpp)
#target_link_libraries(helloworld my_fancy_library)

add_executable(tests tests.cpp)
target_link_libraries(tests m)
