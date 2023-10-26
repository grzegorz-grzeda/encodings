# encodings
[![CMake](https://github.com/grzegorz-grzeda/encodings/actions/workflows/cmake.yml/badge.svg)](https://github.com/grzegorz-grzeda/encodings/actions/workflows/cmake.yml)

Encodings library in C.

This is a [G2EPM](https://github.com/grzegorz-grzeda/g2epm) library.

## Run tests
Just run `./test.sh`.

## How to compile and link it?

Just include this directory in your CMake project. Remember to specify the event handler buffer size.

Example `CMakeLists.txt` content:
```
...

add_subdirectory(<PATH TO ENCODINGS LIBRARY>)

target_link_libraries(${PROJECT_NAME} PRIVATE encodings)

...
```

# Copyright
This library was written by Grzegorz Grzęda, and is distributed under MIT Licence. Check the `LICENSE` file for
more details.