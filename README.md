# MobileNet V2 Image Classification

This repository contains the course assignment implementation for classifying the supplied highway image with a pretrained MobileNet V2 ImageNet model.

## Files

- `MobileNetV2_Image_Classification.ipynb`: end-to-end notebook using TensorFlow Keras MobileNet V2.
- `highway_sample.png`: image supplied for the assignment.
- `MobileNetV2_Assignment_Report_Draft.docx`: report draft. Add screenshots and the actual top-five predictions after running the notebook.

## Run the notebook

Open the notebook in Google Colab or a GitHub Codespace with Jupyter support. Run the cells from top to bottom and upload `highway_sample.png` when prompted. The notebook resizes and preprocesses the image, runs ImageNet inference, prints the top five labels, and plots the top prediction.

The model requires an internet connection the first time so TensorFlow can download pretrained ImageNet weights.
