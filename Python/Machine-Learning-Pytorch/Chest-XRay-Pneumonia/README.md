# Chest X-Ray Pneumonia Classification

## Project Overview

This project uses Deep Learning and Transfer Learning techniques to classify Chest X-Ray images as either **Normal** or **Pneumonia**.

The goal was to compare different pre-trained Convolutional Neural Networks (CNNs) and identify the best-performing model for pneumonia detection.

---

## Dataset

The dataset consists of Chest X-Ray images belonging to two classes:

- Normal
- Pneumonia

Images were preprocessed and loaded using PyTorch DataLoaders for training and evaluation.

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

## Models Evaluated

### ResNet18
- Transfer Learning
- Test Accuracy: **84.84%**

### EfficientNet-B0
- Transfer Learning
- Test Accuracy: **89.84%**
- Best Performing Model

### MobileNetV3 Small
- Transfer Learning
- Test Accuracy: **83.13%**

---

## Model Comparison

| Model | Test Accuracy |
|---------|---------|
| EfficientNet-B0 | 89.84% |
| ResNet18 | 84.84% |
| MobileNetV3 Small | 83.13% |

---

## Training Configuration

- Optimizer: Adam
- Learning Rate: 0.001
- Loss Function: CrossEntropyLoss
- Epochs: 15

---

## Saved Models

The trained model weight are stored in the Models folders and can be loaded for inference or further fine-tuning.

---

## Key Findings

- EfficientNet-B0 achieved the highest overall accuracy.
- ResNet18 produced strong results but misclassified more Normal images.
- MobileNetV3 Small provided faster training but lower accuracy.
- Transfer Learning significantly improved performance on the medical imaging dataset.

---
## Skills Demostrated

- Deep Learning
- Transfer Learning
- Image Classification
- Computer Vision
- Pytorch
- Model Evaluation
- Data Visualization
- Medical Image Analysis

--- 

## Best Performing Model

EfficientNet-B0 achieved the highest test accuracy of 89.84%, outperforming ResNet18 and MobileNetV3

## Future Improvements

- Hyperparameter tuning
- Data augmentation
- Cross-validation
- Grad-CAM explainability
- Web application deployment using Streamlit

---

## Project Structure

```text
Chest-XRay-Pneumonia-Classification/
│
├── README.md
├── Chest_XRay_Pneumonia.ipynb
├── requirements.txt
│
└── models/
    ├── model_0_resnet.pth
    ├── model_1_efficientnet.pth
    └── model_2_mobilenet.pth
```

---

## Author

**Hashsham Abid**

Machine Learning | Deep Learning | Artificial Intelligence
