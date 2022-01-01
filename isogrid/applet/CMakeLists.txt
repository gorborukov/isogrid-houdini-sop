add_library(applet STATIC
  include/applet.h
  include/typedef.h
  include/noise.h
  src/applet.cpp
)

set_property(TARGET applet PROPERTY POSITION_INDEPENDENT_CODE ON)

target_include_directories(applet PUBLIC include)
