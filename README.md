# Brain Tumor Classification using Deep Learning (MRI)

This repository contains a deep learning pipeline for **MRI-based brain tumor classification**.  
The project compares three state-of-the-art convolutional neural networks (**ResNet50**, **VGG16**, and **EfficientNetB0**) using transfer learning to classify MRI scans into three tumor categories:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**

---

## 📂 Dataset
The dataset used is the **Brain Tumor MRI Dataset**, which consists of MRI images grouped into three classes.  

### Preprocessing:
- Images resized to **224×224**
- Split into **70% train / 15% validation / 15% test**
- Data augmentation applied:  
  - Random rotation  
  - Width & height shift  
  - Zoom  
  - Horizontal flip  

 **Features**
-  Automated dataset preprocessing (resizing, splitting, and augmentation)  
-  Transfer learning with **ResNet50, VGG16, EfficientNetB0**  
-  Fine-tuning of top layers for improved accuracy  
-  Training & validation curve visualization (accuracy & loss)  
-  Confusion matrix generation for model performance analysis  
-  Early stopping and best-model checkpointing  
-  Easily extendable to other CNN architectures
  
**Requirements**

This project requires the following libraries:

Python >= 3.8

TensorFlow 2.x

Keras

NumPy

Pandas

Matplotlib

Seaborn

scikit-learn

Pillow

Install everything using:
