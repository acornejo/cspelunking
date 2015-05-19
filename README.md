# Collection of tools to dive into unknown C/C++ codebases

## inctree

Prints out a tree of the `#include` structure of a file (or list of
files).

    $ inctree xf86drm.h
    xf86drm.h
    +--../lib/clang/3.4/include/stdarg.h
    |  +--../lib/clang/3.4/include/stddef.h
    +--../lib/clang/3.4/include/stdint.h
