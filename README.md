# Gravity Engine

A minimal C++ project scaffold for a gravity simulation engine.

## Project structure

- `src/` - library source files
- `include/` - public headers
- `tests/` - unit tests
- `build/` - out-of-source CMake build directory

## Requirements

- CMake 3.15 or newer
- A C++17-compatible compiler

## Build and test

```bash
mkdir -p build
cd build
cmake ..
cmake --build .
ctest --output-on-failure
```

## License

This project is licensed under the MIT License. See `LICENSE` for details.
