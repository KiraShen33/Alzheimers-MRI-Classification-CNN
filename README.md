# Overview

This project develops a Convolutional Neural Network (CNN) model to classify MRI images into different stages of Alzheimer's Disease (AD). The goal is to provide an early and accurate diagnosis tool that can improve treatment strategies and patient quality of life. The project specifically addresses the challenges of class imbalances and intricate model architectures required for high accuracy in medical image analysis.

# Key Features

**Class Imbalance Management:** Implements upsampling techniques to balance the dataset, ensuring equitable learning across all disease stages.
**Custom CNN Architecture:** Tailored convolutional neural network designed to process MRI images effectively.
**Custom Loss Function:** Introduces a novel loss function that reduces the test loss significantly, from 12 to 4, enhancing model accuracy and robustness.
**Performance Metrics:** Achieves a test accuracy of 78.22%, demonstrating strong capability in classifying stages of Alzheimer's Disease.

# Data Description
The dataset includes MRI scans categorized into four stages of Alzheimer's Disease: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. It is sourced from publicly available medical image repositories.
