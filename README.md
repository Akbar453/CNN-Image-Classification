# Image-Classification-using-CNN

# Model Architecture
Input Layer: 256x256x3 images
Conv2D Layers: Three layers with 32, 64, and 128 filters respectively
BatchNormalization & MaxPooling: Applied after each Conv2D layer
Dense Layers: Two fully connected layers with 128 and 64 neurons
Output Layer: Sigmoid activation function for binary classification

# How to Run

Download the dataset from Kaggle and place it in the appropriate directory.
Install dependencies:
pip install tensorflow opencv-python matplotlib
Run the model:
model.fit(train_ds, epochs=10, validation_data=test_ds)

# Results
Training Accuracy: 81%
Validation Accuracy: 81%

# Future Work
Experiment with different architectures and hyperparameters.
Implement data augmentation techniques to improve performance.
