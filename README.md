# Minimum Vulkan Compute Shader Demo + Vulkan Memory Allocator
Demo executes a single compute shader and exits

* Uses [Volk](https://github.com/zeux/volk) as a Vulkan Loader
* Uses [Vulkan Memory Allocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) as a Memory Manager

# Dependencies
* [LunarG SDK](https://vulkan.lunarg.com/)

# How to compile shaders
``` bash
$ glslc -c src/main/glsl/square.comp -o square.comp.spv
```