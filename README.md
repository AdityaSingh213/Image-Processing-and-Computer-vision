# Image-Processing-and-Computer-vision
This repository contains 5 experiments implemented using Python and OpenCV for the Image Processing & Computer Vision Lab.

Tools Used Python OpenCV NumPy Matplotlib

Folder Structure IP-CV │ ├── Experiment-1.py ├── Experiment-2.py ├── Experiment-3.py ├── Experiment-4.py ├── Experiment-5.py │ ├── input_images │ └── sample.jpg │ └── output_images

Experiment 1: Acquire Image

Objective: To read and display an image using OpenCV.

Description: The program loads an image from the input_images folder and displays it on the screen using OpenCV functions.

Input: Sample image

Output: Displayed image and saved output image.

Experiment 2: Sample Quantization

Objective: To reduce the number of intensity levels in an image.

Description: The image is converted into fewer gray levels by dividing pixel values into fixed intervals.

Input: Grayscale image

Output: Quantized image with reduced intensity levels.

Experiment 3: Contrast Stretching and Histogram Equalization

Objective: To enhance the contrast of an image.

Description: Contrast stretching expands the intensity range of an image. Histogram equalization redistributes pixel intensity values for better contrast.

Input: Grayscale image

Output: Contrast enhanced image.

Experiment 4: Low Pass and High Pass Filtering

Objective: To apply smoothing and sharpening filters.

Description: Low pass filtering removes noise and smooths the image. High pass filtering highlights edges and details.

Input: Image

Output: Smoothed image and edge enhanced image.

Experiment 5: Mean, Median and Gaussian Filtering

Objective: To remove noise from an image.

Description: Different filters are applied to a noisy image to reduce noise and improve image quality.

Mean Filter – averages pixel values
Median Filter – removes salt and pepper noise
Gaussian Filter – smooths image using Gaussian distribution

Input: Noisy image

Output: Filtered images
