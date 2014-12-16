# OpenNURBS CMake Build system
# see GNU GENERAL PUBLIC LICENSE, version 2, attached

set(name Caterpillar)

set(sources
  main.cpp
)

add_executable(${name} ${sources})

install(TARGETS Caterpillar DESTINATION bin)

