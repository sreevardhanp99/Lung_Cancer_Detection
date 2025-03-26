# Lung Cancer Detection

## Overview

This project focuses on classifying lung cancer nodules to monitor patients' health. It utilizes a neural network topology combined with the SVM algorithm and compares its accuracy with the K-Means clustering approach. The goal is to build an efficient model for detecting abnormal lung CT scans.

## Features

- **Dataset Handling**: Load and preprocess lung CT scan images.
- **Dimensionality Reduction**: Use PCA to reduce feature dimensions.
- **Machine Learning Models**:
  - **Support Vector Machine (SVM)**: Classifies CT scans as normal or abnormal.
  - **K-Means Clustering**: Groups CT scans and evaluates clustering accuracy.
- **Model Evaluation**: Compare classification accuracy between SVM and K-Means.
- **Prediction Interface**: Load a new CT scan and predict its classification.
- **Results Visualization**: Display accuracy comparison graphs.

## Requirements

To run this project, install the following dependencies:

- Python 3.7+
- pandas
- numpy
- matplotlib
- OpenCV
- scikit-learn
- tkinter

Install dependencies using:

```bash
pip install pandas numpy matplotlib opencv-python scikit-learn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/sreevardhanp99/Lung_Cancer_Classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Lung_Cancer_Classification
   ```

3. Run the Python script:

   ```bash
   python main.py
   ```

4. Perform the following actions via the GUI:

   - Upload the dataset
   - Split data into training and testing sets
   - Train the SVM model
   - Run K-Means clustering
   - Predict lung cancer from a CT scan
   - Visualize model performance

## Contribution

Contributions are welcome! Fork the repository and submit a pull request with your improvements or bug fixes. For major changes, open an issue first to discuss the modifications.



