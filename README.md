# Driver-Detection
In this model , driver images are given . In every images driver is doing some activity in the car . This model perfectly detects what the driver is doing in the picture .

# 🚗 Driver Behavior Classification using CNN

This project involves building a deep learning model to classify driver behaviors based on image data. A custom convolutional neural network (CNN), inspired by ResNet architecture, was trained on real-world driving images to identify various driver postures or actions.

---

## 📂 Dataset

- Real-world image dataset (e.g., driver in different positions like texting, safe driving, etc.)
- Images organized by folders (`imgs/train/`, `imgs/test/`)
- Preprocessed and saved as `.npy` arrays for faster training

---

## 🧠 Model Overview

- **Architecture**: Custom CNN built using Keras Functional API
- **Layers**: Convolution → BatchNorm → ReLU → Pooling → Dense
- **Training Strategy**:
  - Loss: `categorical_crossentropy`
  - Optimizer: `Adam`
  - EarlyStopping & Checkpoint callbacks used
- **Evaluation**:
  - Stratified K-Fold Cross Validation
  - Leave-One-Group-Out (LOGO) validation

---

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- PIL for image handling
- Scikit-learn (for validation)

---

## 🖼️ Key Features

- Converted raw image data into normalized `.npy` arrays
- Plotted class distribution and sample insights
- Built flexible model using Functional API for modularity
- Used advanced cross-validation strategies to ensure robust performance
- Optimized model using regularization & dropout layers

---

## 📊 Results

- Achieved strong classification accuracy across multiple driver behavior classes
- Used confusion matrices and class-wise metrics for detailed evaluation
- Visualized training performance using accuracy/loss plots

---



