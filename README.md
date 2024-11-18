# VulkanTriangle
Learning Vulkan while making my first triangle.

## Description
This is a simple graphical application made using C++ that utilizes the Vulkan API to render a triangle on the screen. This project serves as an introduction to Vulkan's graphics pipeline and demonstrates how to set up a minimal Vulkan application using GLFW for the window management.

### Motivation
I am really interested in learning graphics programming, so I made this project to get into learning the Vulkan API and setting something up for future graphics applications. Vulkan is known for being complex, verbose, and explicit compared to other graphics APIs, making it a truly intriguing first pick for rendering my first triangle.

### What I Learned
- Setting up a Vulkan instance and handling validation layers (debugging).
- Selecting physical and logical devices suitable for rendering.
- Creating and managing swap chain for image presentation.
- Understanding and implementing Vulkan's rendering pipeline.
- Handling synchronization with semaphores and fences.
- Reading and compiling shader code (SPIR-V) for use in the pipeline.
- Managing resources and memory in a Vulkan application.

## Installation
### Prerequisites
- C++ Compiler: A compiler that supports C++ 14 or higher (like GCC, Clang, or MSVC).
- Vulkan SDK: Download the SDK and make sure the drivers are up to date.
- GLFW: Install the GLFW library
- Shader Compiler: Any compiler that can convert GLSL to SPIR-V.

### Steps
1. Clone the repository
2. Install dependencies
3. Compile the vertex and fragment shaders
4. Compile the application

## Usage
1. Run the .exe using ./VulkanTriangle
2. A window should open, displaying a triangle.
3. No controls, but the window can be closed.

![Screenshot 2024-11-18 014329](https://github.com/user-attachments/assets/423c9063-a064-47fb-bc69-233a25e0ccd1)

## Credits
- I worked on this project solo.

## Acknowledgements
- The Vulkan Tutorial - [vulkan-tutorial](https://vulkan-tutorial.com/)
- GLFW Library - [GLFW](https://www.glfw.org/) for window and input management.
- Khronos Group - For developing and maintaining the Vulkan API.
