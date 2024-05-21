
add_library(stb INTERFACE stb/stb_image.h stb/stb_image_write.h)

add_library(stb::stb ALIAS stb)

target_include_directories(stb INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
