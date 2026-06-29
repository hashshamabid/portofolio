# Brain Tumor MRI Classification Using Transfer Learning

## Project Overview

This project focuses on classifying Brain MRI images into four categories using Deep Learning and Transfer Learning techniques.

The objective is to compare the performance of multiple pre-trained Convolutional Neural Networks (CNNs) for automatic brain tumor classification.

Classes:

- No Tumor
- Glioma
- Meningioma
- Pituitary Tumor

The project evaluates and compares the following models:

1. ResNet50
2. VGG16
3. EfficientNet-B3

---

## Technologies Used

- Python
- PyTorch
- TorchVision
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## Dataset

Brain MRI images were used for multi-class classification.

Total Classes:

- No Tumor
- Glioma
- Meningioma
- Pituitary

Images were preprocessed and resized before training.

---

## Project Workflow

### Data Preparation

- Image loading
- Train/Test split
- Image resizing
- Data normalization

### Model Development

Three transfer learning models were implemented:

#### ResNet50

- Pretrained on ImageNet
- Final fully connected layer replaced
- Fine-tuned for 4 output classes

#### VGG16

- Pretrained on ImageNet
- Classifier modified
- Fine-tuned for tumor classification

#### EfficientNet-B3

- Pretrained on ImageNet
- Classification head replaced
- Fine-tuned for MRI classification

---

## Training Configuration

- Loss Function: Cross Entropy Loss
- Optimizer: Adam
- Epochs: 15
- Transfer Learning: Yes
- Framework: PyTorch

---

## Results

### ResNet50

Test Accuracy: Approximately 84%

Results available in:

- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Training Performance

---

### VGG16

Test Accuracy: Approximately 84%

Results available in:

- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Training Performance

---

### EfficientNet-B3

Test Accuracy: Approximately 84%

Results available in:

- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Training Performance

---

## Saved Models

The trained models are included in this repository.

```text
models/
├── brain_tumor_vgg16.pth
├── brain_tumor_efficientnet.pth
└── brain_tumor_densenet.pth
```

---

## Results Folder Structure

```text
Results/
├── Resnet50/
│   ├── Accuracy.png
│   ├── Loss Function.png
│   ├── Confusion Matrix.png
│   └── Training the model.png
│
├── VGG16/
│   ├── Accuracy.png
│   ├── Loss Function.png
│   ├── Confusion Matrix.png
│   └── Training the model.png
│
└── EfficientNET/
    ├── Accuracy.png
    ├── Loss Function.png
    ├── Confusion Matrix.png
    └── Training the model.png
```

---

## Key Findings

- Transfer Learning significantly improved performance.
- Meningioma and Pituitary tumors achieved the highest classification scores.
- Glioma and No Tumor classes showed more overlap and misclassifications.
- ResNet50, VGG16 and EfficientNet-B3 produced comparable results.
- The project demonstrates the effectiveness of Deep Learning for medical image classification.

---

## Future Improvements

- Increase dataset size
- Apply data augmentation techniques
- Fine-tune more layers
- Experiment with DenseNet121 and Vision Transformers (ViT)
- Hyperparameter optimization
- Deploy the model using Streamlit or Flask

---

## Author

Hashsham Abid

GitHub Portfolio Project

Brain Tumor MRI Classification using Transfer Learning and PyTorch.
