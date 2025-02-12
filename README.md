Overview
This project implements a deep learning model for fingerprint-based identity detection and finger number classification. Using Convolutional Neural Networks (CNNs), 
the system can predict the subject ID (from 600 possible identities) and finger number (from 10 possible types) based on fingerprint images. The model is trained on labeled fingerprint data and achieves high accuracy in biometric authentication.

Features
✅ Fingerprint classification for biometric identification
✅ CNN-based deep learning models for subject and finger number prediction
✅ High-accuracy classification using optimized architectures
✅ Model evaluation with confusion matrices and performance metrics


Technologies Used
Python
TensorFlow / Keras
OpenCV (for fingerprint image processing)
NumPy & Pandas
Matplotlib (for visualization)
Model Architecture
Model 0 (Subject ID Prediction): Classifies fingerprint images into 600 possible subject IDs.
Model 1 (Finger Number Prediction): Classifies images into 10 possible finger types.
Both models use Conv2D layers, MaxPooling, Dense layers, L2 regularization, and Dropout to enhance generalization.
Activation Functions: ReLU for hidden layers, Softmax for final classification.
Optimizer: Adam, with Cross-Entropy loss for training.
