# Breast Cancer Detection ML Project

## Overview

This project focuses on detecting **Invasive Ductal Carcinoma (IDC)**, the most prevalent form of breast cancer, using various convolutional neural network (CNN) architectures. The goal is to classify histopathology images as either containing IDC or not, aiding in early and accurate diagnosis.

## Dataset

The dataset used for this project is sourced from Kaggle:

- **Breast Histopathology Images**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images)

This dataset contains 277,524 patches of size 50 x 50 pixels extracted from 162 whole mount slide images of breast cancer specimens. Each image is labeled as **class 0** (no IDC) or **class 1** (contains IDC).

## Models Implemented

The following CNN architectures have been implemented and evaluated:

- Basic CNN
- LeNet
- Inception (GoogLeNet)
- VGG16
- MobileNet
- Xception
- Transformers (using Hugging Face)

## Repository Structure

- `Basic CNN for breast-cancer-image-classification.ipynb`
- `LeNet breast-cancer-image-classification.ipynb`
- `INCEPTION.ipynb`
- `ML PROJECT VGG16.ipynb`
- `MobileNet_BCH.ipynb`
- `XCEPTION ON BCH.ipynb`
- `transformersHF.ipynb`
- `PRESENTATION.pptx`: Summary of project goals and outcomes.

## Environment and Tools

- **Platform**: Kaggle Notebooks with GPU acceleration
- **Libraries**: TensorFlow/Keras, PyTorch, OpenCV, NumPy, Pandas, Matplotlib

## Results

The models were evaluated based on accuracy, precision, recall, and F1-score. Results are available within the respective notebooks.

## How to Use

1. **Download the dataset** from Kaggle and link it to your notebook environment.
2. **Install required libraries** if running locally.
3. **Run any notebook** to test or retrain the models.

## Acknowledgments

Special thanks to Kaggle and the dataset contributors for providing the Breast Histopathology Images dataset.

## License

This project is licensed under the MIT License.
