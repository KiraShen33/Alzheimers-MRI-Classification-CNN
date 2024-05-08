# Overview

This project develops a Convolutional Neural Network (CNN) model to classify MRI images into different stages of Alzheimer's Disease (AD). The goal is to provide an early and accurate diagnosis tool that can improve treatment strategies and patient quality of life. The project specifically addresses the challenges of class imbalances and intricate model architectures required for high accuracy in medical image analysis.

# Requirements

- tensorflow==2.10.0
- keras==2.10.0
- opencv-python
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- pillow

# Key Features

**Class Imbalance Management:** 
  - Implements upsampling techniques to balance the dataset, ensuring equitable learning across all disease stages.

**Custom CNN Architecture:** 
  - Tailored convolutional neural network designed to process MRI images effectively.

**Custom Loss Function:** 
  - Introduces a novel loss function that reduces the test loss significantly, from 12 to 4, enhancing model accuracy and robustness.

**Performance Metrics:** 
  - Achieves a test accuracy of 78.22%, demonstrating strong capability in classifying stages of Alzheimer's Disease.



# Data Description

The dataset includes MRI scans categorized into four stages of Alzheimer's Disease: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. It is sourced from publicly available medical image repositories.
![Screenshot 2024-05-08 at 14 24 59](https://github.com/KiraShen33/Alzheimers-MRI-Classification-CNN/assets/113120686/f76ae513-d08b-4d12-8251-5771293c2439)


# Model Architecture

- **Input Layer:** Accepts an input of 224x224 RGB images.
- **Convolutional and Pooling Layers:** Multiple layers designed to extract and downsample features from the MRI scans.
- **Regularization Techniques:** Utilizes dropout to reduce overfitting and improve generalization.
- **Output Layer:** A dense layer with softmax activation to classify the input into one of the four stages.

# Results

The CNN model effectively classifies Alzheimer's Disease stages with a high accuracy of 78.22%. Detailed analysis and confusion matrix are provided to showcase the model's performance across different stages.

# Contributors
- Qinmiao Deng*
- Kira Shen*
- Xinbei Yu*
- Kaishuo Zhang*

*Each person equally contributed to this project.

Contact: {qinmiao_deng, ruiqi_shen, xinbei_yu, kaishuo_zhang, qi_zhao}@brown.edu

