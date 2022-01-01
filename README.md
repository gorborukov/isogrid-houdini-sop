** Linux compatible version **
# isogrid Houdini SOP

![A](https://media.giphy.com/media/Yrfx3lUESu9V9YG2VO/giphy.gif)
![B](https://media.giphy.com/media/dXQhYcHP9n1EVtsorT/giphy.gif)

This is a C++ port of [isogrid](https://github.com/wblut/isogrid) Processing library by [wblut](https://twitter.com/wblut) with a Houdini plugin.

## Requirements

- CMake
- C++ compiler

## Build

From the repository folder:

```
    mkdir build ; cd build
    cmake .. -DHFS="~/houdini18.5"
    cmake --build . --config Release
```

You additionally can set `HOUDINI_DSO_DIR` variable if your configuration folder is not default.
