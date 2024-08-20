# Skin-Disease-Detection

## Overview
This project focuses on developing a deep learning-based system to detect and classify various skin diseases. The system leverages transfer learning to achieve high accuracy, making it suitable for practical applications in the medical field.

## Dataset
The dataset used for this project contains images representing different types of skin diseases. Each image is labeled with the corresponding disease class, providing a robust dataset for model training and evaluation.
- Number of Images: ~4,000
- Number of Classes: 31
the dataset can be download from the following link: https://drive.google.com/drive/folders/1AiDVpgy-o4ZLKXZ_yqnWWEHFYhCbrfP1

## Model Architecture
### Transfer Learning Models Tested
Before selecting the final model, we tested the dataset on the following transfer learning models:
- ResNet50
- DenseNet121
- VGG16
- InceptionV3
- Xception

Final Model: DenseNet121 + Inception
After evaluating the performance of the above models, the final model chosen is a combination of DenseNet121 and Inception. This hybrid approach was selected due to its superior performance in terms of accuracy and generalization on the dataset.
The DenseNet121 + Inception model demonstrated strong performance across various metrics, outperforming the individual models tested. Detailed evaluation metrics and comparison charts can be found in the notebooks directory of this repository.

