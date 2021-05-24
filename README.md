This is the source code for the [Using CMake and managing dependencies](https://eliasdaler.github.io/using-cmake/).

It shows how to setup a simple project which depends on SFML, Dear ImGui and ImGui-SFML.

# Building

```sh
git clone https://github.com/eliasdaler/cmake-fetchcontent-tutorial-code
mkdir build && cd build
cmake ../cmake-fetchcontent-tutorial-code
cmake --build .
./src/example_exe # or ./src/Debug/example_exe if using Visual Studio
```
