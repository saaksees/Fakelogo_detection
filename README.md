# Real vs Fake News Logo Classifier 📰🔍

This project uses **deep learning and computer vision** to classify news as **real or fake** based on its logo or visual identity using **ResNet50**.

##  Files
- `realfakelogo.ipynb`: Kaggle notebook with all code and results

##  Models & Methods
- Pretrained **ResNet50** CNN from Keras
- Image preprocessing with `ImageDataGenerator`
- Model fine-tuning and evaluation using accuracy and loss curves

##  Dataset
- Custom dataset of **news logos labeled as real or fake**
- Organized into `/train/real`, `/train/fake`, `/val/real`, and `/val/fake` directories

##  Key Results
- Achieved high accuracy on validation data
- Model learns visual features associated with credible and fake sources

##  Requirements
See `requirements.txt` for dependencies.

---

Created by Saakshi Jaiswal
