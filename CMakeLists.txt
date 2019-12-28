project(lab5)

set(CMAKE_CXX_STANDARD 17)

add_executable(lab5
  ./main.cpp)

set(CMAKE_CXX_FLAGS
  "${CMAKE_CXX_FLAGS} -Wall -Wextra")