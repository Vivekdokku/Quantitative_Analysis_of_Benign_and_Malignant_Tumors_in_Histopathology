# Quantitative_Analysis_of_Benign_and_Malignant_Tumors_in_Histopathology

# Cancer Detection Using SVM Classifiers

This project implements a cancer detection system using Support Vector Machine (SVM) classifiers. It is designed to classify medical images into different grades of cancer severity. The project is structured to handle different categories of cancer and utilizes grid search with cross-validation to optimize the SVM parameters for the best performance.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Validation](#validation)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop a robust cancer detection system using machine learning techniques, specifically Support Vector Machines (SVMs). The system is capable of classifying images into various categories, representing different grades of cancer severity. This can assist medical professionals in early detection and diagnosis of cancer, leading to better patient outcomes.

## Dataset

The dataset used in this project consists of medical images categorized into different grades of cancer severity:
- Benign
- Grade 3
- Grade 4
- Grade 5
- Grade 345 (a combination of grades 3, 4, and 5)

The images are resized to 150x150 pixels and flattened to create feature vectors for training the SVM classifiers.

## Installation

To run this project, you need to have the following libraries installed:
- pandas
- scikit-image
- numpy
- matplotlib
- scikit-learn
- tqdm

You can install these libraries using pip:

```bash
pip install pandas scikit-image numpy matplotlib scikit-learn tqdm

## About the Project

### Overview

This project aims to develop a robust system for detecting and classifying cancer using medical images. Leveraging the power of Support Vector Machines (SVM), the system is designed to distinguish between different grades of cancer severity with high accuracy. The primary goal is to assist medical professionals in the early detection and accurate diagnosis of cancer, potentially leading to better patient outcomes and more effective treatment plans.

### Key Features

- **Multi-Category Classification**: The project classifies medical images into multiple categories, representing different grades of cancer severity, including benign cases.
- **SVM Classifiers**: Utilizes Support Vector Machine classifiers, optimized using grid search with cross-validation, to achieve high accuracy in predictions.
- **Image Preprocessing**: Involves resizing and flattening medical images to create feature vectors suitable for SVM training.
- **Parameter Optimization**: Employs GridSearchCV to find the optimal parameters (C, gamma, and kernel) for the SVM classifiers, ensuring the best performance.
- **High Accuracy**: Achieves notable accuracy rates for different classifiers, demonstrating the effectiveness of SVMs in medical image classification.

### Methodology

1. **Data Collection**: The dataset comprises medical images categorized into different grades of cancer: Benign, Grade 3, Grade 4, Grade 5, and a combined Grade 345.
2. **Image Preprocessing**: Images are resized to 150x150 pixels and flattened to create feature vectors, which are then used for training the SVM classifiers.
3. **Training the Models**: Three separate SVM classifiers are trained to distinguish between different categories:
    - **Classifier C1**: Distinguishes between Benign and Grade 345 with 97.22% accuracy.
    - **Classifier C2**: Differentiates between Grade 3 and Grade 45 with 100.0% accuracy.
    - **Classifier C3**: Separates Grade 4 from Grade 5 with 70.0% accuracy.
4. **Validation**: The trained models are validated using a separate set of images to evaluate their accuracy and reliability.

### Results

The project achieves significant accuracy rates in classifying cancer severity, showcasing the potential of SVMs in medical image analysis:

- **Classifier C1**: 97.22% accuracy
- **Classifier C2**: 100.0% accuracy
- **Classifier C3**: 70.0% accuracy

These results underline the effectiveness of the developed system in distinguishing between different grades of cancer, particularly in identifying benign cases versus malignant ones.

### Future Enhancements

To further improve the system, future work may include:
- **Expanding the Dataset**: Incorporating a larger dataset with more diverse images and additional categories.
- **Exploring Alternative Models**: Investigating other machine learning models and advanced techniques for better accuracy.
- **User Interface Development**: Creating a more user-friendly interface to facilitate usage by medical professionals.

### Conclusion

This project demonstrates a promising approach to cancer detection using machine learning, specifically SVM classifiers. By providing high accuracy in classifying cancer severity, the system can play a crucial role in aiding early diagnosis and improving patient care.

For more details on how to use the project, see the [Usage](#usage) section.
