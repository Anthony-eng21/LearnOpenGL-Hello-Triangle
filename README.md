# OpenGL Boilerplate

Minimal OpenGL 3.3 project with CMake, GLFW, GLAD, and GLM.

## Requirements

- C++ Compiler (Clang)
- CMake 3.15+
- GLFW
- GLAD
- GLM

## Setup

Install via Homebrew:
```
xcode-select --install
brew install cmake glfw glm
```

**Get GLAD**:

1. Go to https://glad.dav1d.de/
2. Select: gl 3.3, Core, check Generate a loader
3. Click Generate and download ZIP
4. Extract files to:
   - include/glad/ → vendor/glad/include/glad/
   - include/KHR/ → vendor/glad/include/KHR/
   - src/glad.c → vendor/glad/src/glad.c

## Build & Run
```
    // first time
    cmake -S . -B build
    cmake --build build
    ./build/OpenGL_App

    **Rebuild & Run**
    cmake --build build && ./build/OpenGL_App

```
## Resources

- LearnOpenGL.com - https://learnopengl.com/