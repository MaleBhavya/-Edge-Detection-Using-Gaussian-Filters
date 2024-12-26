Edge Detection using Gaussian Filters

Overview
This project applies Gaussian smoothing and derivatives for edge detection in grayscale images. It includes techniques like gradient magnitude computation, non-maximum suppression, and hysteresis thresholding for refined edge maps.

Setup
1. Install required libraries:
pip install numpy matplotlib opencv-python-headless scipy

2. Place your grayscale image (e.g., 67079.jpg) in the correct path (/content/ by default).

Usage
Run the script to process the image using Gaussian filters with predefined sigma values (0.7, 0.9, 1.0). The program outputs smoothed images, edge maps, and orientation visualizations.
