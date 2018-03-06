# Include path
include_directories(${CMAKE_CURRENT_SOURCE_DIR})

# Add executables
## tests
add_executable(test_app test.c)
target_link_libraries(test_app dubins)

add_executable(test_cli test-cli.c)
target_link_libraries(test_cli dubins)
