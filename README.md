# Project to experiment with C++ modules

This repository has a submodule. Must init/update submodules before building.

To configure & build with CMake:

    md build & cd build & cmake -G"Visual Studio 16 2019" -Ax64 ..\
    msbuild ball_pit.sln /t:ball_pit

Binary will be output in `build/Debug`
