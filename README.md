# Simple C++ Project
Template for a simple C++ project

## How to build:
```
$ cd build
$ cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=1 -Wno-dev ..
$ make
```

where:
- `-DCMAKE_EXPORT_COMPILE_COMMANDS=1` is for clangd
- `-Wno-dev` is for suppressing some warnings

## How to run:
```
$ cd bin
$ ./main
```
