link_libraries(glfw)
link_libraries(m)

include_directories("deps")
set(GLAD "deps/glad/glad.h"
         "deps/glad.c")

add_executable(boing boing.c ${GLAD})
add_executable(gears gears.c ${GLAD})
add_executable(heightmap heightmap.c ${GLAD})
add_executable(simple simple.c ${GLAD})
add_executable(splitview splitview.c ${GLAD})
add_executable(wave wave.c ${GLAD})
