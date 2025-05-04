# DEEP-LEARNING-PROJECT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JAYESH MODHVADIYA

*INTERN ID*: CT4MDA791

*DOMAIN*: DATA SCIENCE

*DURATION*: 4 MONTHS

*MENTOR*: NEELA SANTOSH


A deep learning project for image classification using a Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset. Built with PyTorch, this model includes data augmentation, dropout regularization, and achieves improved accuracy over training epochs.

## 📌 Features

- Deep CNN architecture with 3 convolutional layers
- Data augmentation (random flip, rotation)
- Dropout for regularization
- CIFAR-10 image dataset (10 classes)
- Adam optimizer for faster convergence
- Visualization of predictions

## 📁 Dataset

- [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html): 60,000 32x32 color images in 10 classes, with 6,000 images per class.

## 🧠 Model Architecture

<pre>text
Input → Conv2D(32) → ReLU → MaxPool
     → Conv2D(64) → ReLU → MaxPool
     → Conv2D(128) → ReLU → MaxPool
     → Flatten → FC(512) → ReLU → Dropout
     → FC(128) → ReLU → FC(10) → Output</pre>

🚀 Getting Started
# 1. Clone the repository
  - bash
  - Copy
  - Edit
  - git clone https://github.com/your-username/deep-cnn-image-cifar10-classification.git
  - cd deep-cnn-image-cifar10-classification
# 2. Install dependencies
  - bash
  - Copy
  - Edit
  - pip install torch torchvision matplotlib
# 3. Run the training script
  - bash
  - Copy
  - Edit
  - python main.py
# 4. Visualize Predictions
  - Predictions for test images will be shown using matplotlib.

# Result:
| Epoch | Loss ↓ |
| ----- | ------ |
| 1     |  2.08  |
| 5     |  1.12  |
| 10    |  1.02  |

<pre># Output
- True labels:      cat   ship       ship  airplane
- Predicted labels: cat   automobile ship  airplane</pre>

# Output:
![Image](https://github.com/user-attachments/assets/e69e2b1a-6b59-4fc8-93a1-dcef55386390)

