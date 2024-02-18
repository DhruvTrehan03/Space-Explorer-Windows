# Space Explorer
Developing a game about a spaceship.

Using OpenGL C++

### Build project:
```
cmake -S . -B build
```
From /build:
```
make
./Space_Explorer
```

### For Dhruv's laptop (Windows)
In CMakeLists:
    cmake_minimum_required(VERSION 3.0.0) -> cmake_minimum_required(VERSION 3.5.0)
    project(Space_Explorer LANGUAGES C CXX)
    Include 'PUBLIC res' and 'PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include/entities' under target_include_directories(${PROJECT_NAME}
In Shaders.hpp:
    #include <unordered_map>
In shader.cpp
    #include <string>


terminal: cmake -S . -B .
Build
Run