# Classkinfy
# Skin disease classification using Smartphone Images and Deep Learning

## Overview
This repository is an implementation of a skin disease classification system using smartphone camera images, image processing, and deep learning techniques. The system uses image processing with a CNN based on a modified EfficientNet architecture to classify multi-category skin disease. The system is designed to support offline model evaluation and real time inference with a lightweight backend. 
The primary objective of this project of this porject is to investigate the effectiveness of deep learning image classication for dermatological analysis using non clinical image, such as smartphone images, while still trying to solve challenges relating to image quality, class imbalance and visual similarity among skin diseases. 


---

## Research Objectives
- To develop an automated skin disease classification system using smartphone images  
- To evaluate the performance of deep learning models on multi-class dermatological data  
- To analyze the impact of preprocessing and data augmentation on classification accuracy  
- To provide a research-oriented system suitable for early decision support  

---

## Dataset
This study uses the **HAM10000 (Human Against Machine with 10000 training images)** dataset, which consists of dermatoscopic images representing seven categories of skin lesions:

- Actinic Keratosis (AKIEC)  
- Basal Cell Carcinoma (BCC)  
- Benign Keratosis (BKL)  
- Dermatofibroma (DF)  
- Melanoma (MEL)  
- Melanocytic Nevi (NV)  
- Vascular Lesions (VASC)  

---

## Methodology Overview
1. Image preprocessing (resizing, normalization, hair removal, noise reduction)  
2. Data augmentation and class imbalance handling  
3. Deep learning–based classification using a modified EfficientNet architecture  
4. Model training and validation using PyTorch  
5. Performance evaluation using accuracy, precision, recall, and F1-score  
6. Deployment of an inference backend using FastAPI and Uvicorn  

---

## System Features
- Multi-class skin disease classification using CNN  
- Robust preprocessing pipeline for smartphone images  
- Feature-based preliminary prediction for fast initial inference  
- Backend API for real-time prediction  
- Research-oriented design for reproducibility and evaluation  

---

## Technologies Used
- Python  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- FastAPI  
- Uvicorn  

---

## Competition Information
This project was developed as part of the OPSI (Olimpiade Penelitian Siswa Indonesia) competition, focusing on application of artificial intelligence and image processing in healthcare. 

---

## Disclaimer
This system is intended for research and educational purposes only. It is not a medical diagnostic tool and should not be used as a substitute for professional medical diagnosis.
