# **Image Classification using Attention of Convolution (ConvNet - VGG16)**

This repository contains an **image classification model** leveraging the **VGG16 architecture** with an **attention mechanism** to enhance feature extraction and classification accuracy. The project includes **image processing, model training using TensorFlow, and heatmap visualization** to interpret model predictions effectively.

---

## **Introduction**
This project focuses on **image classification** using a **VGG16-based Convolutional Neural Network (ConvNet)** integrated with an **attention mechanism** to improve feature extraction. The model is trained on a labeled dataset and employs **heatmap visualization** for better interpretability.

---

## **Features**
✅ Preprocessing techniques for image enhancement  
✅ VGG16-based ConvNet with an **attention mechanism**  
✅ Model training & evaluation using **TensorFlow**  
✅ **Heatmap visualization** to interpret model decisions  
✅ Optimized hyperparameters for improved accuracy  

---

## **Dataset & Preprocessing**
### **Dataset**
The model is trained on a labeled image dataset. The dataset should be organized as follows:

### **Preprocessing Steps**
- **Resizing** images to match **VGG16 input size (224x224)**
- **Normalization**: Pixel values scaled between 0 and 1  
- **Data Augmentation**: Applied techniques such as **rotation, flipping, zooming, and shifting** to improve model generalization  

---

## **Model Architecture**
- **Base Model**: Pretrained **VGG16**
- **Attention Mechanism**: Applied on convolutional feature maps to emphasize important regions
- **Fully Connected Layers**: Dense layers with dropout to prevent overfitting
- **Output Layer**: Softmax activation for multi-class classification
