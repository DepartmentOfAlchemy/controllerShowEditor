The ControllerShowEditor is a tool to allow you to create a show for a prop controller. It will allow you to define an ambient and triggered scenes. Each scene can have an audio track and sequenced outputs.

This is the beginning of the project. It is in an alpha stage of definition and experimentation. This will hopefully transform into a useful project.

## Building the Project

# Debug

Follow these steps to build the project:

1. **Create a build directory & configure the build:**
   ```bash
   cmake -Ssrc -Bbuild
   ```

2. **Build the project:**
   ```bash
   cmake --build build -j
   ```

Artifacts will be generated in the `build` directory. For instance, for Windows you will find `build\Debug\main.exe` is the executable to run.