# Handwritten Character Recognition using CNN

## Project Overview

This project implements a Handwritten Character Recognition system using a Convolutional Neural Network (CNN) and the MNIST dataset. The objective is to automatically recognize handwritten digits (0–9) from images.

The project was developed as part of the CodeAlpha Machine Learning Internship.

---

## Objective

To build a deep learning model capable of accurately recognizing handwritten digits from image data.

---

## Dataset

**MNIST Handwritten Digits Dataset**

* Total Images: 70,000
* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Classes: 10 (Digits 0–9)

The dataset is directly available through TensorFlow/Keras.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

The MNIST dataset was loaded using TensorFlow's built-in dataset loader.

### 2. Data Preprocessing

* Normalized pixel values from 0–255 to 0–1.
* Reshaped images to fit CNN input requirements.

### 3. Model Development

A Convolutional Neural Network (CNN) was developed using:

* Conv2D Layer
* MaxPooling2D Layer
* Flatten Layer
* Dense Hidden Layer
* Output Layer with Softmax Activation

### 4. Model Training

The CNN model was trained using:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 5

### 5. Model Evaluation

The model was evaluated using test data and achieved high classification accuracy.

### 6. Predictions

The trained model successfully predicted handwritten digits from unseen images.

### 7. Visualization

The following visualizations were generated:

* Sample MNIST Images
* Predicted Digits
* Confusion Matrix

---

## Model Architecture

Input Layer (28×28×1)

↓

Conv2D (32 Filters, 3×3 Kernel, ReLU)

↓

MaxPooling2D (2×2)

↓

Flatten Layer

↓

Dense Layer (128 Neurons, ReLU)

↓

Output Layer (10 Neurons, Softmax)

---

## Results

The CNN model achieved excellent performance on the MNIST test dataset.

Performance Metrics:

* Test Accuracy: ~98% to 99%
* Multi-class Classification of Digits 0–9
* Successful Prediction on Unseen Handwritten Images

---

## Output Files

Generated files include:

* Handwritten_Character_Recognition.ipynb
* handwritten_model.h5

---

## Future Improvements

* Extend recognition from digits to alphabets using EMNIST.
* Develop a real-time handwriting recognition application.
* Deploy the model using Flask or Streamlit.

---

## Conclusion

A Convolutional Neural Network (CNN) was successfully developed for handwritten digit recognition using the MNIST dataset.

The model demonstrated high accuracy and strong generalization performance on unseen data. This project showcases the application of Deep Learning and Computer Vision techniques for image classification tasks.

---

## Author

Vivek Vipparla

CodeAlpha Machine Learning Internship
