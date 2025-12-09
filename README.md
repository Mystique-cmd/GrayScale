# Grayscale Image Converter

This is a C++ application that demonstrates various image processing techniques using OpenGL. The application loads an image, displays the original, a grayscale version, and a version with an animated color filter.

## Features

*   **Image Loading:** Loads a PNG image using the `stb_image` library.
*   **Original Image Display:** Shows the original image on the left side of the window.
*   **Grayscale Conversion:** Converts the image to grayscale and displays it in the middle of the window.
*   **Color Filtering:** Applies a color filter with an animated hue shift and displays it on the right side of the window.

## Dependencies

The project has the following dependencies:

*   **C++17 Compiler**
*   **CMake 3.10+**
*   **OpenGL**
*   **GLEW**
*   **glfw3**
*   **glm**

## Building and Running

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Grayscale-Image-Converter
```

### 2. Install Dependencies

Ensure you have the required dependencies installed on your system. For example, on a Debian-based Linux distribution, you can install them using:

```bash
sudo apt-get update
sudo apt-get install build-essential cmake libglm-dev libglew-dev libglfw3-dev
```

### 3. Build the Project

Create a build directory and run CMake:

```bash
mkdir build
cd build
cmake ..
make
```

### 4. Run the Application

Before running the application, make sure you have an image named `image.png` in the `src` directory.

```bash
./app
```

## Usage

Once the application is running, you will see a window with three versions of the image:

*   **Left:** The original image.
*   **Middle:** The grayscale version of the image.
*   **Right:** The color-filtered version of the image with an animated hue shift.

Press the `ESC` key to close the window.
