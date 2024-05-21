# STB-IMage

## stb image (header only minimal library)

## CMake

```cmake
add_excuetable(YoutProject ...)

add_subdirectroy(stb)

target_link_libraries(YourProject PUBLIC|INTERFACE|PRIVATE stb)
```

## CPP
```cpp
#define STB_IMAGE_IMPLEMENTATION
#include <stb/stb_image.h>
#include <stb/stb_image_write.h>
```