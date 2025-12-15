# Face Liveness Detection Using Deep Learning

## Project Overview
This project implements a **Face Liveness Detection system** that can distinguish between real faces and spoofed/fake faces (e.g., printed photos or videos). It is designed to enhance **security in facial authentication systems** by preventing spoofing attacks.  

The project is implemented in **Python** using **Jupyter Notebook**, with deep learning and computer vision techniques. The dataset used consists of **images collected personally by the developer**.

---

## Features
- Detects real vs fake faces from images or video frames.
- Preprocessing of facial images using OpenCV.
- CNN-based deep learning model for binary classification.
- Easy-to-run Jupyter Notebook for training and testing.

---

## Project Structure
FaceLiveness/
├── face_liveness.ipynb       # Main Jupyter Notebook with all code and explanations
├── requirements.txt          # Lists all Python packages required to run the notebook
├── README.md                 # This file, explains the project
└── data/                     # Folder for your images
    ├── real/                 # Subfolder containing real face images
    └── fake/                 # Subfolder containing spoofed/fake face images
