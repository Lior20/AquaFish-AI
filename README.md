# 🐟 AquaFish-AI

> Early Warning for Invasive Fishes: Protecting the Mediterranean Through AI-Powered Image Classification

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-orange.svg)](https://pytorch.org/)

## 📋 Overview

This repository contains the implementation of an AI-powered system for detecting and classifying invasive fish species in the Mediterranean Sea. The project utilizes state-of-the-art deep learning techniques, combining YOLOv9 for object detection and various CNN architectures for classification.

## 🚀 Features

### 🔍 Fish Detection
- Advanced fish detection using YOLOv9 object detection model
- Real-time processing capabilities
- High accuracy in complex underwater environments
- Comprehensive evaluation metrics including mAP

### 🎯 Fish Classification
- Multi-model approach using:
  - DenseNet (94.45% accuracy)
  - GoogLeNet (94.17% accuracy)
  - ResNet (92.77% accuracy)
  - VGG-19 (90.80% accuracy)
- Transfer learning optimization
- Robust performance on underwater imagery

## 🛠️ Getting Started

### Prerequisites
```bash
python >= 3.8
pytorch >= 2.0
roboflow
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Lior20/AquaFish-AI.git
cd AquaFish-AI
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Dataset Preparation

#### For Detection:
1. Navigate to `Detector.ipynb`
2. Follow instructions to download the dataset from Roboflow
3. Configure paths as needed

#### For Classification:
1. Download the FDFML dataset
2. Update paths in `fish_classifier.ipynb`

## 📊 Model Performance

| Model | Test Accuracy | F1-Score |
|-------|--------------|-----------|
| DenseNet | 94.45% | 0.9609 |
| GoogLeNet | 94.17% | 0.9448 |
| ResNet | 92.77% | 0.9535 |
| VGG-19 | 90.80% | 0.9458 |

## 📓 Notebooks

- `Detector.ipynb`: Implementation of YOLOv9 fish detection
- `fish_classifier.ipynb`: Species classification using various CNN architectures

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- YOLOv9 by SkalskiP
- PyTorch team
- Roboflow platform
- FDFML Dataset by Swinburne University of Technology
- Tel Aviv University Department of Electrical Engineering

## 📝 Citation

If you use this work in your research, please cite:
```bibtex
@article{benishay2024early,
  title={Early Warning for Invasive Fishes: Protecting the Mediterranean Through AI-Powered Image Classification},
  author={Ben Ishay, Lior and Druker, Keren},
  institution={Tel Aviv University},
  year={2024}
}
```
