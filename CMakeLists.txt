# CMake Version
cmake_minimum_required( VERSION 3.22 )

project( Hello VERSION 0.1.3 LANGUAGES C CXX )

set(Headers
    "src/headers/main.hpp"
)

set(Sources
    "src/sources/main.cpp"
)

add_executable( app ${Headers} ${Sources} )

