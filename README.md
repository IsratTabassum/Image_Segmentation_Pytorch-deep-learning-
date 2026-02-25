# Image Segmentation using U-Net (PyTorch)

This project implements an Image Segmentation model using the U-Net architecture in PyTorch. The model performs pixel-wise classification to generate segmentation masks from input images.

## 🚀 Project Overview

The objective of this project is to build and train a deep learning model capable of accurately segmenting objects within images. The implementation was done using PyTorch and executed in Google Colab.

## 🧠 Model Architecture

- U-Net architecture
- Encoder-decoder structure with skip connections
- Designed for semantic segmentation tasks

## 📊 Loss Function

To improve segmentation performance, a combination of:

- Binary Cross-Entropy (BCE) Loss
- Dice Loss

was used. This helps balance pixel-level accuracy and region overlap performance.

## 🛠 Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Google Colab

## 📈 Training & Evaluation

- Data preprocessing and transformation
- Model training and validation
- Performance evaluation using Dice score
- Visualization of predicted masks vs ground truth

## 🔍 Results

The model successfully learned meaningful segmentation patterns and produced accurate mask predictions. 



---

Feel free to explore and contribute!
