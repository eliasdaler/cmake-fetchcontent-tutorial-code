This is the source code for the [Using CMake and managing dependencies](https://edw.is/using-cmake/).

It shows how to setup a simple project which depends on SFML, Dear ImGui and ImGui-SFML.

![image](https://user-images.githubusercontent.com/1285136/119359595-76e74280-bcb2-11eb-9ad5-1e69795e5696.png)

# Building

```sh
git clone https://github.com/eliasdaler/cmake-fetchcontent-tutorial-code
mkdir build && cd build
cmake ../cmake-fetchcontent-tutorial-code
cmake --build .
./src/example_exe # or ./src/Debug/example_exe if using Visual Studio
```
