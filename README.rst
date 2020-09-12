CMake - MinGW as default generator
*****

this is fork from [Kitware/CMake] (https://github.com/Kitware/CMake)

the difference is default generator is ``MinGW Makefiles`` if ``g++.exe`` is in ``%PATH%``.
I am too lazy to type generator every time, and don't want to add extra environment variable.

``MinGW Makfiles`` generator has highest priority if other Windows compilers exist in your system.

all changes are in ``mingw64-default`` branch, merge to cmake release tag if you want get latest CMake.
