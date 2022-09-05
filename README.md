# CMake Generator

[Premake](https://github.com/premake/premake-core) extension for supporting [cmake](http://www.cmake.org/) cmake

## Features

* Support for C/C++ language projects
* Work in progress

## Install

In your project directory copy this directory.

add this line to your premake5.lua:

```lua
require("cmake")
```

## Usage

Simply generate your project using the `cmake` action:

```bash
premake5 cmake
```
