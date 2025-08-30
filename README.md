# Lung-Disease-Detection
Transfer Learning on Vgg19

Built this project under guidance of Prof. Nikunja Kar as a part of my coursework<br> 


Multi-class Lung Disease Prediction <br>
This repository implements multiple deep learning models through papers for detecting lung diseases from chest X-ray images.It includes MobileNetV2, DenseNet-121, and a DenseNet+VGG fusion approach.


##  Models Implemented

###  MobileLungNetV2
- Modified MobileNetV2 with **data augmentation** and **Grad-CAM visualization**.
- Reference: [PubMed Article](#)

###  DenseNet-121 for COVID Detection
- Uses DenseNet-121 with preprocessing.  
- Reference: [MDPI Article](#)

###  DenseNet + VGG Fusion
- Feature fusion approach combining DenseNet and VGG features.  
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

