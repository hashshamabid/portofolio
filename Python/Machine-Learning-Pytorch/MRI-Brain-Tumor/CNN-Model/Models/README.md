This folder contains the trained model weights for the custom Convolutional Neural Network (CNN) developed for Brain Tumor MRI Classification.

## Files

- CNN_brain_tumor.pth

## Description

The model was trained using MRI brain scan images and saved in PyTorch `.pth` format.

## Usage

Load the model weights using PyTorch:

```python
model.load_state_dict(torch.load("CNN_brain_tumor.pth"))
model.eval()
