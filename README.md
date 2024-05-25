# AquaFish-AI
Deep Learning course - Final project

This repository contains the implementation of the paper " EARLY WARNING FOR INVASIVE FISHES: PROTECTING THE MEDITERRANEAN THROUGH AI-POWERED IMAGE CLASSIFICATION "

# Fish Detection and Classification
This repository contains code for detecting and classifying fish species using YOLOv9 object detection and transfer learning on pre-trained models for classification. The code is written in Python and utilizes PyTorch, Roboflow, and other popular libraries.

## Features

### Fish Detection
- Fish detection using YOLOv9 object detection model
- Training and evaluation scripts for the detection task
- Visualization of training results, confusion matrix, and sample detections

### Fish Classification
- Fish classification using transfer learning on pre-trained models (DenseNet, GoogLeNet, ResNet, ViT, VGG)
- Training and evaluation scripts for the classification task
- Visualization of training logs, confusion matrices, and sample predictions

## Getting Started

1. Clone the repository:

git clone https://github.com/Lior20/AquaFish-AI.git
  cd AquaFish-AI

2. Prepare the dataset:

  For detection, follow the instructions in the Copy_of_Detector_YOLOv9_Fish_NoFish.ipynb notebook to download the dataset from Roboflow.
  For classification, download the FDFML dataset and update the paths in the fish_classifier_2 - Copy.ipynb notebook.


3. Run the notebooks:

  Fish Detection: Detector.ipynb
  Fish Classification: fish_classifier.ipynb



Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
Acknowledgments

YOLOv9 by SkalskiP
PyTorch
Roboflow
FDFML Dataset by Swinburne University of Technology
