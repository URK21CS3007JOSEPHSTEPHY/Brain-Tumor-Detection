# Brain Tumor Detection using Deep Learning

This project aims to detect brain tumors from MRI images using deep learning techniques. Two popular convolutional neural network (CNN) architectures, namely ResNet-50 and VGG16, are employed for this purpose. The models are trained using MRI images obtained from the Kaggle dataset.

## Dataset
The dataset used in this project is sourced from Kaggle and contains a collection of brain MRI images with and without tumors. It consists of a total of 3000 images.

## Models
Two deep learning models are utilized for brain tumor detection:
1. **ResNet-50**: A state-of-the-art CNN architecture known for its depth, which helps in capturing intricate features effectively.
2. **VGG16**: A classic CNN architecture known for its simplicity and effectiveness in various computer vision tasks.

## Training
The models are trained using the following configurations:
- Optimizer: Adam optimizer
- Loss Function: Binary Cross-Entropy
- Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Specificity
  - Validation loss

## Results
The performance of both models is evaluated using various metrics, including accuracy, precision, recall, F1-score, specificity, and validation loss.

