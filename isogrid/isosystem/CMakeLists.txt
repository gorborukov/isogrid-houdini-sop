add_library(isosystem STATIC
  include/isogrid.h

  src/isogrid.cpp
  src/iso_applet.h
  src/iso_applet.cpp
  src/iso_system.h
  src/iso_system.cpp
)

set_property(TARGET isosystem PROPERTY POSITION_INDEPENDENT_CODE ON)

target_include_directories(isosystem PUBLIC include)
target_link_libraries(isosystem PRIVATE applet isogrid)
