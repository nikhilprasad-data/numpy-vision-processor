# 👁️ NumPy Vision Processor

## 🚀 Overview
A lightweight, from-scratch computer vision and image processing pipeline engineered entirely using **Core NumPy**. 

Instead of relying on high-level abstraction libraries like OpenCV, this project demonstrates a fundamental understanding of **Linear Algebra** by treating images as 3D matrices (Tensors) and applying mathematical transformations, slicing, and shifting directly at the pixel-array level.

## 🛠️ Tech Stack & Architecture
* **Language:** Python 3.x
* **Core Engine:** NumPy (Matrix Operations, Array Broadcasting)
* **Visualization:** Matplotlib
* **Image I/O:** Pillow (PIL)

## 📂 Pipeline Structure & Features

### 1. `01_vision_preprocessing.ipynb` (Matrix Slicing & ROI)
Focuses on raw data extraction and manipulation.
* Loads high-resolution images as NumPy multi-dimensional arrays.
* Performs highly optimized mathematical slicing to extract precise Regions of Interest (ROI) without memory overhead.
* Exports structured, cropped matrices back into standardized image formats (`processed_bike_001.jpg`, etc.).

### 2. `02_vision_filters.ipynb` (Mathematical Edge Detection)
Focuses on advanced feature extraction using custom mathematical logic.
* Implements edge detection and gradient mapping *from scratch*.
* Utilizes array translation (shifting matrices up/down/left/right) and computes the absolute differences to identify boundaries and pixel-intensity gradients.
* Proves core competency in mathematical convolutions without importing external CV filters.

## ⚙️ Local Setup & Installation

To run this mathematical engine on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nikhilprasad-data/numpy-vision-processor.git
   ```

2. **Set up the virtual environment (Recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks:**
   Launch Jupyter environment and execute the preprocessing and filter pipelines step-by-step.

## 🎯 Key Learning & Impact
This project acts as a mathematical sandbox for understanding how deep learning models (like CNNs) fundamentally perceive and manipulate image data through kernels, tensors, and matrix multiplications.