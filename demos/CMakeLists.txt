# Include path
include_directories(${CMAKE_CURRENT_SOURCE_DIR})

# Add executables
## demo
add_executable(demo_app demo.c)
target_link_libraries(demo_app dubins)
