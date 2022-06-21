# cpp-fmt-example

Experimental example for use of the fmt C++ library per CMake package management.

## Usage

Generate build files:

```console
❯ cmake -S . -B build
# ...
```

Build:

```console
❯ cmake --build build
[ 20%] Building CXX object _deps/fmt-build/CMakeFiles/fmt.dir/src/format.cc.o
[ 40%] Building CXX object _deps/fmt-build/CMakeFiles/fmt.dir/src/os.cc.o
[ 60%] Linking CXX static library libfmt.a
[ 60%] Built target fmt
[ 80%] Building CXX object CMakeFiles/fmt_example.dir/main.cpp.o
[100%] Linking CXX executable fmt_example
[100%] Built target fmt_example
```

Execute basic example:

```console
❯ build/fmt_example
Hello, 42!
```
## Status

Experimental

**Note**: The default branch is `default`.
