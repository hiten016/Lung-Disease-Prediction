# Lung-Disease-Prediction
Transfer Learning on Vgg19


Multi-class Lung Disease Prediction <br>
This repository implements multiple deep learning models through papers for detecting lung diseases from chest X-ray images.It includes MobileNetV2, DenseNet-121, and a DenseNet+VGG fusion approach.


##  Models Implemented

### 🔹 MobileLungNetV2
- Modified MobileNetV2 with **data augmentation** and **Grad-CAM visualization**.
- Achieved **96.97% accuracy**.  
- Reference: [PubMed Article](#)

### 🔹 DenseNet-121 for COVID Detection
- Uses DenseNet-121 with preprocessing.  
- Achieved **97% accuracy**.  
- Reference: [MDPI Article](#)

### 🔹 DenseNet + VGG Fusion
- Feature fusion approach combining DenseNet and VGG features.  
- Achieved **98% accuracy**.  
- Reference: [PubMed Article](#)

## Folder

├── data/                  
│   └── lung_disease_dataset/
│       ├── bacterial_pneumonia/
│       ├── covid19/
│       ├── normal/
│       ├── tuberculosis/
│       └── viral_pneumonia/
├── outputs/               
├── src/                 
│   ├── dataset.py          
│   ├── gradcam.py         
│   ├── model_densenet.py  
│   ├── model_fusion.py   
│   ├── model_mobilenet.py  
│   ├── train.py           
│   └── utils.py         
├── main.py             
├── README.md
├── requirements.txt
└── venv/                 

Dataset used: https://www.kaggle.com/datasets/dionixius/lung-disease-5-class-dataset 
