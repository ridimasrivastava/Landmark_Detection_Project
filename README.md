# Google Landmark Detection using TensorFlow

## Overview

This project implements a Landmark Detection system using TensorFlow and Computer Vision techniques. The model is trained to identify famous landmarks from images and classify them into their corresponding landmark categories.

The project demonstrates image preprocessing, feature extraction, model training, evaluation, and prediction using deep learning.

---

## Features

- Landmark image classification
- Deep learning with TensorFlow/Keras
- Image preprocessing and augmentation
- Model training and evaluation
- Prediction on unseen landmark images
- Performance visualization

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The project uses the Google Landmark Dataset containing thousands of landmark images from around the world.

Dataset Components:
- Landmark Images
- Landmark IDs
- Training Labels
- Validation Images

---

## Project Workflow

1. Load and preprocess image dataset
2. Perform image augmentation
3. Build TensorFlow CNN model
4. Train the model on landmark images
5. Evaluate model performance
6. Generate predictions
7. Visualize classification results

---

## Model Architecture

The model utilizes Convolutional Neural Networks (CNNs) for feature extraction and landmark classification.

Key Components:
- Convolution Layers
- Max Pooling Layers
- Dense Layers
- Softmax Classification Layer

---

## Results

The trained model can:

- Identify landmarks from images
- Predict landmark categories
- Generate confidence scores
- Generalize to unseen landmark images

---

## Usage

Open the notebook:

```bash
jupyter notebook Landmark_Detection.ipynb
```

Run all cells sequentially to:

- Load dataset
- Train model
- Evaluate performance
- Predict landmark classes

---

## Sample Output

Input Image → Landmark Prediction

Example:

- Eiffel Tower → Correctly Classified
- Taj Mahal → Correctly Classified
- Statue of Liberty → Correctly Classified

---

## Future Improvements

- Use Transfer Learning (EfficientNet, ResNet)
- Increase dataset size
- Improve classification accuracy
- Deploy as a web application
- Real-time landmark recognition

---