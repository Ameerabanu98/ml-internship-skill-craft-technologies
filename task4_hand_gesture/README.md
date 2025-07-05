# Hand Gesture Recognition

## 🔍 Overview
This project detects hand gestures (digits 0–9) using a Convolutional Neural Network (CNN). It can be used for gesture-based control, sign language recognition, and human-computer interaction.

## 🗂️ Folder Structure
- train/          → Training images (folders 0 to 9)
- test1/          → Test images
- hand_gesture_model.h5  → Trained model
- hand gesture  jpg image file
- README.md       → Project documentation

## 🧠 Model Details
- Architecture: CNN
- Input shape: 64x64x3
- Activation: ReLU, Softmax
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Metric: Accuracy


## ✅ Observations
- The model was able to learn basic gesture patterns.
- Real-time prediction using webcam was functional.
- However, accuracy on test images was inconsistent due to:
  - Varying lighting conditions
  - Background noise
  - Limited training data

## 🔧 Areas for Improvement
- Increase dataset size with more diverse images
- Apply data augmentation (rotation, flip, zoom)
- Use background removal or segmentation
- Fine-tune model with more convolutional layers or dropout
- Experiment with other models like ResNet or MobileNet

## 📌 Next Steps
- Collect more data in different environments
- Train with advanced models for better generalization
- Try deploying on mobile using TensorFlow Lite

## 👤 Author
- Name: Ameera Banu
- GitHub: https://github.com/Ameerabanu98


