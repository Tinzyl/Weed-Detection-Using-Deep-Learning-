# 🌿 Weed Detection Using Deep Learning

This project leverages deep learning to classify images into four categories: **broadleaf**, **grass**, **soil**, and **soybean**. The model is built using **TensorFlow** and **Keras**. 🚀

---

## 🌟 Project Highlights

- **Image Augmentation**: Enhanced dataset diversity using transformations. 🖼️
- **Custom CNN Architecture**: Built a convolutional neural network from scratch. 🤖
- **High Accuracy**: Achieved over **96% validation accuracy**. 📈
- **Model Saving and Deployment**: Saved the model for real-world use. 💾

---

📊 **Data Preparation**

- Image Augmentation: Applied transformations like:
1. Rescaling: Normalize pixel values to a [0,1] range.
2. Shear and Zoom Transformations.
3. Horizontal Flip for variance.
4. Train-Test Split:
    - Training Data: 80% of the images.
    - Validation Data: 20% of the images.
---

🤖 **Model Architecture**

1. Convolutional layers with ReLU activation.
2. Max-pooling layers for down-sampling.
3. Dense (fully connected) layers for classification.
4. Dropout to prevent overfitting.
5. Optimizer: Adam
6. Loss Function: Categorical Crossentropy
---

🧪 **Model Performance**

Training Accuracy: 95.96%
Validation Accuracy: 96.09%
Epochs: 20
Batch Size: 128

