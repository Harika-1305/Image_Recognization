# Image_Recognization
# 🔢 Handwritten Digit Classification using MLP (MNIST)

## 📌 Project Overview
This project classifies handwritten digits (0–9) using a Multi-Layer Perceptron (MLP) classifier. It demonstrates neural network-based classification using the MNIST dataset.

## 📊 Dataset
- Dataset: MNIST (from TensorFlow/Keras)
- Training samples: 60,000 images  
- Testing samples: 10,000 images  
- Image size: 28 × 28 pixels (grayscale)

## ⚙️ Technologies Used
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras  

## 🚀 Steps Performed
1. Imported required libraries  
2. Loaded MNIST dataset  
3. Reshaped images (28×28 → 784 features)  
4. Normalized pixel values (0–255 → 0–1)  
5. Built MLP Classifier model  
6. Trained model using training data  
7. Predicted labels for test data  
8. Evaluated model using classification report  
9. Visualized predictions  

## 🧠 Model Details
- Algorithm: MLPClassifier (Neural Network)  
- Hidden Layers: (128, 64)  
- Activation Function: ReLU  
- Optimizer: Adam  
- Batch Size: 128  
- Iterations: 20  

## 📈 Performance
- Accuracy: **98%**  
- High precision, recall, and F1-score across all digits  

## 📊 Visualization
- Displays sample test images with predicted labels  
- Helps verify model performance visually  

## 📁 Project Structure
