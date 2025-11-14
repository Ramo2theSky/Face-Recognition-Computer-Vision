# Face Recognition — Computer Vision Assignment

This repository contains an individual assignment for the Computer Vision course, focusing on implementing a simple face recognition pipeline using Eigenfaces for feature extraction and a basic classifier for recognition.

---

## Author
**Muhammad Yusuf Ramadhan**  
NIM: 23/517172/PA/22158

---

## Project Overview

This project demonstrates a complete face recognition workflow using classical computer vision techniques. The pipeline includes:

### 1. Face Detection
- Load face images from a local dataset  
- Detect face regions using OpenCV  

### 2. Face Cropping
- Crop detected face areas to isolate the subject  

### 3. Image Preprocessing
- Convert images into grayscale  
- Resize face regions to a uniform resolution  
- Flatten images into 1D vectors  

### 4. Train–Test Split
- Split the data into training and testing sets  

### 5. Data Normalization
- Compute mean face  
- Mean-center all training images  

### 6. Feature Extraction (Eigenfaces)
- Perform Principal Component Analysis (PCA)  
- Extract eigenfaces as principal components  
- Project images into the PCA feature space  

### 7. Classification
- Train a simple classifier (e.g., nearest neighbor)  
- Evaluate recognition accuracy  

---

## How to Run

1. Prepare a local dataset of face images.  
2. Open and execute all cells in:  
   **`Computer_Vision_1.ipynb`**  
3. Ensure all dependencies are installed (see below).  

---

## Dependencies

Install required libraries:

```bash
pip install numpy matplotlib scikit-learn opencv-python
