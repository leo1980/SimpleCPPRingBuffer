
cmake_minimum_required (VERSION 2.6)
project (SimpleCPPRingBuffer)

include_directories("${PROJECT_SOURCE_DIR}")

set(SRC example.cpp)

# add the executable
add_executable(example  ${SRC})

