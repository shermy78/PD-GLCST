# PD-GLCST: Parkinson’s Disease Detection

## Overview
This repository contains the **PD-GLCST** model, a Graph Learning-based Convolutional Sparse Transformer designed for **early Parkinson’s disease detection** using **handwritten images and sensor signals**.

## 🔧 Installation
1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/PD-GLCST-Parkinsons-Detection.git
   cd PD-GLCST-Parkinsons-Detection
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## 🚀 Usage
### **Training**
Run the training script:
```
python train.py
```
### **Evaluation**
Run the evaluation script:
```
python evaluate.py
```
### **Inference**
Run inference on new images:
```
python inference.py --image_path example.png
```

## 📂 Dataset
Datasets used:
- [HandPD Dataset](https://www.kaggle.com/datasets/claytonteybauru/spiral-handpd)
- [PaHaW Dataset](https://bdalab.utko.fekt.vut.cz/)
- [NewHandPD Dataset](https://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/)

## 📜 License
This project is released under the MIT License.
