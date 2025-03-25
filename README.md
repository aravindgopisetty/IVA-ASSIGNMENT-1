# IVA-ASSIGNMENT-1
# Image Processing and Computer Vision with OpenCV

This notebook delves into the fascinating world of image processing and computer vision using the powerful OpenCV library in Python. It provides a hands-on exploration of various techniques, allowing you to understand and apply fundamental concepts in this field.

## Table of Contents

1. **Color Detection:** This section demonstrates how to isolate specific colors from an image. By leveraging color spaces (like HSV) and thresholding techniques, you'll learn how to extract regions of interest based on their color properties. We'll illustrate this with an example of detecting red objects within an image.

2. **T-Pyramid Computation:** Explore the concept of image pyramids by constructing a T-pyramid (Gaussian Pyramid). This technique involves downsampling an image iteratively, creating representations at multiple resolutions. Understand the applications of image pyramids in various computer vision tasks, such as image blending and object detection.

3. **Image Smoothing:** Learn how to reduce noise and unwanted details in images using smoothing filters. We'll cover different techniques like mean blur, Gaussian blur, and median blur, explaining their properties and trade-offs. By applying these techniques, you'll enhance image quality and prepare them for further processing.

4. **Edge Detection:** This section focuses on identifying sharp changes in intensity within an image, which represent edges. We'll explore two popular edge detection algorithms: Sobel and Canny. You'll understand their strengths and weaknesses and how to apply them effectively to extract meaningful information from images.

5. **Object Detection:** Discover the power of object detection using Haar cascade classifiers. This technique allows us to identify specific objects within an image, such as faces and eyes. We'll guide you through the process of loading pre-trained classifiers and applying them to detect objects in real-time.

## Requirements

To run this notebook, you need to have the following libraries installed:

- Python 3.x: The programming language used in this notebook.
- OpenCV (`cv2`): The core library for image processing and computer vision tasks.
- NumPy (`numpy`): Essential for numerical computations and array operations.
- Matplotlib (`matplotlib`): Used for visualizing images and results.

You can install these libraries using pip:
