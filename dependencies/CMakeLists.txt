include(FetchContent)

# SFML
FetchContent_Declare(
  sfml
  URL https://github.com/SFML/SFML/archive/refs/tags/2.5.1.zip
  URL_MD5 2c4438b3e5b2d81a6e626ecf72bf75be
)
add_subdirectory(sfml)

# Dear ImGui
FetchContent_Declare(
  imgui
  GIT_REPOSITORY https://github.com/ocornut/imgui
  GIT_TAG 35b1148efb839381b84de9290d9caf0b66ad7d03 # 1.82
)

FetchContent_MakeAvailable(imgui)

# ImGui-SFML
FetchContent_Declare(
  imgui-sfml
  GIT_REPOSITORY https://github.com/SFML/imgui-sfml
  GIT_TAG 82dc2033e51b8323857c3ae1cf1f458b3a933c35 # 2.3
)
add_subdirectory(imgui-sfml)
