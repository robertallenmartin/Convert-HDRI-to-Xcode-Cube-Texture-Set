# Convert HDRI to Xcode Cube Texture Set

A Python script for Blender that converts a single 360° panoramic HDRI image into six individual images, formatted for use in an Xcode Cube Texture Set. 

This script automates the process of rendering cube faces from a panoramic HDRI, allowing you to create skyboxes for Xcode projects. You can use the resulting cube texture for background and environment lighting in a SceneKit scene or in shaders using the Metal API.

[![Watch a Demonstration](https://img.youtube.com/vi/f6Dg8RNBqKY/maxresdefault.jpg)](https://www.youtube.com/watch?v=f6Dg8RNBqKY)

## How to Use:
1. Open the Blender file.
2. Navigate to the **Scripting** tab and locate the "render_image" script.
3. Run the script.
4. You will be prompted to select an HDRI file from your machine.
5. The HDRI file will load into the **Environment Texture Node** in the Shader Editor.
6. The script will automatically render the cube faces and save the images in a folder named `output_images` within the project directory.

The resulting images can be used in Xcode as part of a Cube Texture Set for SceneKit or Metal API applications.

[Poly Haven HDRIs](https://polyhaven.com/hdris)

[Check out my YouTube channel for other videos.](https://www.youtube.com/@heyrobertmartin/videos)

