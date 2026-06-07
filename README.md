# 👁️ NumPy Vision Processor

## 🚀 Overview

A computer vision and image preprocessing project built primarily with NumPy to understand how images can be represented and manipulated as multidimensional arrays.

Instead of relying on high-level computer vision libraries for image transformations, this project focuses on performing image preprocessing and basic edge detection operations directly on pixel data using NumPy arrays, slicing techniques, and matrix-based computations.

---

## 🛠️ Tech Stack

* Python 3.x
* NumPy
* Matplotlib
* Pillow (PIL)
* Jupyter Notebook

---

## 📁 Project Structure

```text
numpy-vision-processor/
│
├── image/
│   ├── raw/
│   │   ├── raw_bike_001.jpg
│   │   ├── raw_bike_002.jpg
│   │   └── raw_bike_003.jpg
│   │
│   └── processed/
│       ├── processed_bike_001.jpg
│       ├── processed_bike_002.jpg
│       └── processed_bike_003.jpg
│
├── notebooks/
│   ├── 01_vision_preprocessing.ipynb
│   └── 02_vision_filters.ipynb
│
├── src/
│
├── .env
├── .gitignore
├── README.md
└── requirements.txt
```

---

## 📂 Pipeline Structure & Features

### 1️⃣ `01_vision_preprocessing.ipynb`

### Image Preprocessing & Region Extraction

This notebook focuses on loading image data and performing preprocessing operations using NumPy arrays.

#### Features

* Loads images as multidimensional NumPy arrays
* Inspects image dimensions and pixel information
* Extracts Regions of Interest (ROI) using array slicing
* Crops selected image sections
* Saves processed outputs as new image files
* Demonstrates efficient matrix-based image manipulation

---

### 2️⃣ `02_vision_filters.ipynb`

### Edge Detection Using NumPy

This notebook focuses on understanding image gradients through matrix operations.

#### Features

* Implements basic edge detection logic using NumPy
* Performs directional matrix shifting
* Computes pixel intensity differences
* Identifies image boundaries and edge regions
* Visualizes intermediate and final outputs
* Demonstrates how image filters can be approximated through array operations

---

## ⚙️ Local Setup & Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/nikhilprasad-data/numpy-vision-processor.git
cd numpy-vision-processor
```

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 3: Activate the Environment

#### Windows

```powershell
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

Run the notebooks in the following order:

1. `01_vision_preprocessing.ipynb`
2. `02_vision_filters.ipynb`

---

## 🎯 What I Learned From This Project

This project was created to strengthen my understanding of how image data is represented and processed at the array level before using higher-level computer vision frameworks.

While building this project, I gained hands-on experience in:

* Working with multidimensional NumPy arrays
* Understanding image representations as pixel matrices
* Performing image slicing and region extraction
* Manipulating image data using array indexing
* Applying matrix shifting techniques
* Computing pixel intensity differences
* Building simple edge detection logic from scratch
* Visualizing image transformations with Matplotlib

One of the most valuable lessons from this project was understanding that many computer vision operations are fundamentally matrix operations performed on pixel data. Working directly with NumPy helped me better understand the underlying concepts behind image preprocessing, filtering, and feature extraction.

This project strengthened my understanding of NumPy, image processing fundamentals, and the mathematical operations that form the foundation of modern computer vision workflows.