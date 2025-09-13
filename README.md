# IPCV Project 2025

## 📚 Assignment Module One: Product Recognition of Books

This notebook presents a system for detecting multiple instances of books in bookshelf images. Given a model image of a book and a target scene, the algorithm identifies all occurrences of the book in the scene and highlights them with bounding boxes. The detection pipeline leverages keypoint matching, affine transformations, and RANSAC for robust localization.

**Key Features:**
- Input: Model image + target scene
- Output: Scene image with bounding boxes for detected books
- Uses OpenCV, NumPy, and Matplotlib
- Helper functions for homography estimation and scene projection

## 🐶 Assignment Module Two: Oxford Pet Dataset Classification

This notebook tackles image classification using the Oxford Pet Dataset. It includes data loading, augmentation, model building, training, and evaluation.

**Key Features:**
- Dataset: Oxford Pet Dataset (cats and dogs)
- Deep learning with PyTorch and torchvision
- Data augmentation and visualization
- Model evaluation with confusion matrix and classification report
