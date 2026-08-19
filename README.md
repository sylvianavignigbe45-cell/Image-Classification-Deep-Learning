# Image Classification with Deep Learning

## 📌 Project Overview

This project uses Deep Learning to classify images from the Fashion-MNIST dataset into different clothing categories.

A Neural Network was built using TensorFlow and Keras to learn patterns from images and predict their corresponding classes.

The project was developed and tested using Google Colab.

## 🎯 Project Objectives

- Load and explore the Fashion-MNIST dataset
- Visualize sample images
- Analyze class distribution
- Normalize image pixel values
- Build a Neural Network
- Train the Deep Learning model
- Evaluate model performance
- Generate image predictions
- Analyze prediction confidence
- Visualize correct and incorrect predictions

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn
- Google Colab

## 🧠 Dataset

The project uses the Fashion-MNIST dataset.

The dataset contains 10 clothing categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

Each image has a resolution of 28 × 28 pixels.

## 🤖 Deep Learning Model

The project uses a Neural Network with:

- Flatten layer
- Dense layer with 128 neurons
- Dropout layer
- Dense layer with 64 neurons
- Dropout layer
- Output layer with 10 neurons

The model uses:

- ReLU activation
- Softmax activation
- Adam optimizer
- Sparse Categorical Crossentropy loss

## 🔄 Deep Learning Pipeline

Fashion-MNIST Dataset
        ↓
Data Loading
        ↓
Data Exploration
        ↓
Image Visualization
        ↓
Pixel Normalization
        ↓
Neural Network
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Image Prediction
        ↓
Confusion Matrix
        ↓
Prediction Analysis

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Loss
- Precision
- Recall
- F1-score
- Confusion Matrix

Training and validation performance are also visualized using accuracy and loss curves.

## 🔍 Prediction Analysis

The project analyzes:

- Correct predictions
- Incorrect predictions
- Prediction confidence
- Confusion between different clothing categories

## 💾 Generated Files

The notebook generates:

- fashion_mnist_predictions.csv
- training_history.csv
- fashion_mnist_classifier.keras

These files contain prediction results, training history, and the trained neural network model.

## 📂 Project Structure

Image-Classification-Deep-Learning/
│
├── Image_Classification_Deep_Learning.ipynb
├── README.md
└── requirements.txt

## ▶️ How to Run the Project

1. Open `Image_Classification_Deep_Learning.ipynb` in Google Colab.
2. Run the notebook from beginning to end.
3. The Fashion-MNIST dataset will be downloaded automatically.
4. The images will be normalized and prepared.
5. The Neural Network will be trained.
6. The model will generate predictions.
7. Evaluation metrics and visualizations will be displayed.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Deep Learning fundamentals
- Neural Networks
- Image classification
- TensorFlow and Keras
- Data preprocessing
- Image normalization
- Model training
- Model evaluation
- Confusion matrix analysis
- Prediction confidence analysis
- Data visualization

## 👩🏽‍💻 Author

**Sylviana VIGNIGBE**

B.Tech Computer Science & Engineering  
Specialization: Artificial Intelligence & Machine Learning

## 📚 Project Purpose

This project was created as part of my learning journey in Data Science, Machine Learning, Deep Learning, Computer Vision, and Artificial Intelligence.
