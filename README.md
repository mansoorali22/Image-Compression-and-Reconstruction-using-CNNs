# Image-Compression-and-Reconstruction-using-CNNs

This repository contains the implementation of a project focused on building and experimenting with neural network architectures for image compression and reconstruction. The primary goal is to understand the effects of different neural network configurations on image compression quality and to gain hands-on experience in designing neural networks from scratch.

---

## Objective

The main objectives of this project are:
1. To construct neural networks from scratch and explore their configurations.
2. To experiment with various architectures and layers to study their impact on image compression and reconstruction.
3. To evaluate the performance of the models using quantitative metrics and analyze trade-offs between complexity, training time, and accuracy.

---

## Dataset

- **Dataset**: [LIVE Image Compression Dataset (LIVE 1)](https://live.ece.utexas.edu/research/quality/live_image_compression.html)
- **Description**: The dataset consists of pairs of original and JPEG-compressed images, serving as inputs and target outputs for training and evaluation.

---

## Project Workflow

### 1. Data Exploration and Preprocessing
- Explore the LIVE Image Compression Dataset.
- Preprocess the images by resizing, normalizing, and preparing them for input into the neural network.

### 2. Neural Network Implementation
- Build a neural network architecture from scratch using **NumPy** or **PyTorch**.
- Start with a simple architecture and gradually add complexity:
  - Include layers such as convolutional layers, pooling layers, and dense layers.
  - Experiment with configurations:
    - Number of layers
    - Types of layers (e.g., convolutional, dropout, batch normalization)
    - Activation functions (e.g., ReLU, Sigmoid)
    - Layer arrangements

### 3. Training Process
- Train the model using:
  - Original images as inputs.
  - JPEG-compressed images as target outputs.
- Implement techniques to improve training stability and performance:
  - Learning rate adjustments
  - Batch normalization
  - Dropout

### 4. Evaluation of Results
- Evaluate model performance by reconstructing images and comparing them to the original images.
- Use the following metrics for quantitative assessment:
  - **Peak Signal-to-Noise Ratio (PSNR)**
  - **Structural Similarity Index (SSIM)**
- Analyze the effects of architectural changes (e.g., adding layers, modifying layer types, changing activation functions) on reconstruction quality.

### 5. Analysis
- Discuss the trade-offs between:
  - Model complexity
  - Training time
  - Reconstruction accuracy
- Provide insights into best practices for building effective neural networks for image compression tasks.

---