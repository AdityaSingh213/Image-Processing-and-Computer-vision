# 📸 Image Processing & Computer Vision Lab

This repository contains **5 experiments** implemented using **Python** and **OpenCV** as part of the *Image Processing & Computer Vision Lab*.

---

## 🛠️ Tools & Technologies

* Python
* OpenCV
* NumPy
* Matplotlib

---

## 📂 Folder Structure

```
IP-CV/
│
├── Experiment-1.py
├── Experiment-2.py
├── Experiment-3.py
├── Experiment-4.py
├── Experiment-5.py
│
├── input_images/
│   └── sample.jpg
│
└── output_images/
```

---

## 🔬 Experiments

### 🧪 Experiment 1: Acquire Image

**Objective:**
To read and display an image using OpenCV.

**Description:**
Loads an image from the `input_images` folder and displays it using OpenCV functions.

**Input:** Sample image
**Output:** Displayed image and saved output image

---

### 🧪 Experiment 2: Sample Quantization

**Objective:**
To reduce the number of intensity levels in an image.

**Description:**
Converts the image into fewer gray levels by grouping pixel values into fixed intervals.

**Input:** Grayscale image
**Output:** Quantized image with reduced intensity levels

---

### 🧪 Experiment 3: Contrast Stretching & Histogram Equalization

**Objective:**
To enhance image contrast.

**Description:**

* **Contrast Stretching:** Expands intensity range
* **Histogram Equalization:** Redistributes pixel values for better visibility

**Input:** Grayscale image
**Output:** Contrast-enhanced image

---

### 🧪 Experiment 4: Low Pass & High Pass Filtering

**Objective:**
To apply smoothing and sharpening filters.

**Description:**

* **Low Pass Filter:** Removes noise and smooths the image
* **High Pass Filter:** Enhances edges and fine details

**Input:** Image
**Output:** Smoothed image and edge-enhanced image

---

### 🧪 Experiment 5: Mean, Median & Gaussian Filtering

**Objective:**
To remove noise from an image.

**Description:**

* **Mean Filter:** Averages pixel values
* **Median Filter:** Removes salt-and-pepper noise
* **Gaussian Filter:** Smooths image using Gaussian distribution

**Input:** Noisy image
**Output:** Filtered images with reduced noise

---

## 🚀 How to Run

1. Install required libraries:

   ```bash
   pip install opencv-python numpy matplotlib
   ```

2. Run any experiment:

   ```bash
   python Experiment-1.py
   ```

---

## ✨ Features

* Beginner-friendly implementations
* Covers core image processing techniques
* Clean and modular code structure

---

## 📌 Author

Aditya Singh

---

⭐ *If you found this helpful, consider giving it a star!*

