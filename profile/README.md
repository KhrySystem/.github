# KhrySystem Computing

## About
  KhrySystem is a 3D game development company in Ohio, USA. We focus on providing concise, simple APIs to do complex things. Our current focus is [DragonEngine](https://github.com/KhrySystem/Dragon), A C++ Vulkan Game Engine, able to be extended to many other facets of the computer graphics world, like VR, AR, XR, computer vision, physics simulations, and other topics as they come to publicity in computing. 

## Contributing to Repositories

### Bug Reports
  When contributing to a repository as a response to a bug report, please note the number ID of the report. This helps us greatly when approving contributions to the SDK specifications we have. 
  
### Feature Requests
  In the case of feature requests, we look at how that would be accomplished before and after adding the API calls requested. If it simplifies without bogging down the SDK with excessive, single-use-case code, we will add it, and put it on the develpopment TODO page. 

## Resources
  Our website is located [here](https://khrysystem.dev) for information on SDKs, released version downloads, forums, released games, and information about what's in the works for us right now.

### Backend Libraries Required for Our SDKs

  The [Khronos Group](https://khronos.org) ([github](https://github.com/KhronosGroup)) has many repositories required for Dragon and other libraries we have in development. 
  - [Boost](https://boost.org) ([github](https://github.com/boostlibs/boost)) is one of the most versatile C++ projects you will ever see. Several submodules are required for various libraries.
  - [Vulkan SDK](https://vulkan.lunarg.com) ([github](https://github.com/KhronosGroup/Vulkan-Headers)) is the graphics ABI behind Dragon. 
  - [CMake](https://cmake.org) is required when building any of our projects from source, or when using our FindDragon.cmake module. 
  
### Recommended Libraries for extended functionality
  - [OpenCL](https://www.khronos.org/opencl) ([github](https://github.com/KhronosGroup/OpenCL-Headers)) is the computational mastermind behind Dragon's Thunderbreath extension. Extremely useful for high performance parallel computes.
  - [DotNet](https://dotnet.microsoft.com) or [Mono C#](https://www.mono-project.com) is a dependency for Dragon's Lightbreath extension when building from source. Required for the networking functionality it brings. 
  - [Doxygen](https://doxygen.nl) is a documentation builder that is needed when building certain projects from source. 
  
