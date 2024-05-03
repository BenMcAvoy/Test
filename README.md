# ImGui Playground

This is a playground for ImGui. It is a simple project that demonstrates how to use ImGui in a C++ project with [GLFW](https://www.glfw.org/) and [CMake](https://cmake.org/).

Code should be put in the `src/custom.cpp` file. It also has a variable called `overwriteDefaultWindows` that can be set to `true` to overwrite the default windows that are created by the playground.

The `src/main.cpp` file is the entry point of the application.

## Usage
Press `Use this template` > `Create a new repository` and name it. It is recommend that your repository be public as if you make it private you will either have to configure the todo issue to use a token or remove it.

It is also recommend to rename the project, this can be done by going into `CMakeLists.txt` in the root of the project and changing the project name like so: `project(ImGuiPlayground)` -> `project(MyProject)`.

## Building
You can build the project using [CMake](https://cmake.org/). Here is how you can build the project:
```bash
cmake -B build .
cd build
make
```

The project will be built in the `build` directory and is cross-platform.
