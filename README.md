# Stereo Vision for Depth Estimation and 3D Reconstruction

## Project Overview

“Stereo Vision for Depth Estimation and 3D Reconstruction” is a computer vision project developed by Satyabrat that focuses on reconstructing three-dimensional (3D) scenes from two-dimensional (2D) stereo images.
Using OpenCV’s StereoBM and StereoSGBM algorithms, the project computes disparity maps — special grayscale images that capture pixel-wise depth information.
These disparity values are then reprojected into 3D space, allowing the visualization of real-world structures in depth and dimension.

This project demonstrates how machines can perceive depth similar to human binocular vision, bridging the gap between 2D image data and 3D understanding.
Through this implementation, Satyabrat successfully showcased how AI and computer vision can be used for applications such as autonomous navigation, robotics, AR/VR environments, and medical imaging.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Disparity Maps](#disparity-maps)
- [Real-Life Applications](#real-life-applications)
- [License](#license)


## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone <https://github.com/Aryan-Chharia/Computer-Vision-Projects/pull/222>
   cd ai-3d-reconstruction
 
## Installing Required Libraries 

pip install opencv-python opencv-contrib-python numpy matplotlib


## Prepare your image and run the script like this 

python main.py --input <path_to_your_images> 

## What's Disparity Map ?

Think of how you see the world with both eyes. Each eye views things from a slightly different angle, helping your brain gauge depth. 
Disparity maps do the same for computers! By comparing two or more images taken from different viewpoints, they highlight the differences in object positions. It’s this smart technique that enables computers to turn flat images into stunning 3D models!

## Why Disparity Map Matter ?

Bringing 3D to Life: Disparity maps are the backbone of 3D reconstruction. They give depth to our flat images, helping us create realistic 3D models.
Smart Detection: They allow computers to recognize and track objects in space, making applications smarter and more responsive.
Navigating the World: In robotics and autonomous vehicles, disparity maps help detect obstacles and measure distances, making navigation safer.

## Real Life Application 

In image you can see FADED BLACK and FADED WHITE: What do they mean ?

Faded Black: Think of this as the "faraway land" on the map. Areas that appear faded black indicate low disparity values, meaning those objects are quite distant from the camera. 
Faded White: This is the "up-close and personal" area! Faded white regions indicate high disparity values, signifying that these objects are close to the camera. They usually appear clearer and more detailed, allowing us to capture the essence of the subject.

## Let's connect

I’d love to hear your thoughts or answer any questions you might have! Feel free to reach out or contribute to the project. Together, we can make AI-powered 3D reconstruction even better!
