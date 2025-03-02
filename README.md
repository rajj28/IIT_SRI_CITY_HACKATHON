# 3D IMAGE SEGMENTATION FOR BRAIN TUMOR DETECTION


🚀 Project Overview

Brain tumor resection requires precise planning to minimize damage to healthy tissue. This project leverages deep learning (U-Net) for brain tumor segmentation from MRI scans and reconstructs a 3D visualization to assist neurosurgeons in planning tumor removal procedures effectively.

🎯 Key Features

AI-driven Segmentation: Automated tumor detection from MRI scans using a U-Net model.

3D Tumor Visualization: Converts segmented data into a 3D model for better spatial understanding.

Multi-class Segmentation: Identifies necrotic core, edema, and enhancing tumor regions.

Feasibility & Scalability: Works with real-world MRI datasets and can be expanded to other tumor types.

📌 Problem Statement

Traditional tumor segmentation is manual, time-consuming, and error-prone. This project automates the process using deep learning & generative AI, enhancing precision and reducing surgical risks.

🔬 Technologies Used

Deep Learning: TensorFlow & Keras (U-Net for segmentation)

Medical Imaging: NIfTI format MRI scans (BraTS dataset)

3D Visualization: Vedo, Matplotlib, and PyVista

Data Processing: NumPy, OpenCV, and SimpleITK

Deployment: Google Colab / Jupyter Notebook


![Tumor Visualization](https://github.com/srivabhi22/BrainSegmentor/blob/main/Brain%20tumor%20visualization.png)

## Model Architecture

![Unet3D](https://github.com/srivabhi22/BrainSegmentor/blob/main/u-net-architecture.png)

## Requirements
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15.0-brightgreen)
![Keras](https://img.shields.io/badge/Keras-2.4.3-orange)
![NumPy](https://img.shields.io/badge/NumPy-1.21.2-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-yellow)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-lightgrey)
![Plotly](https://img.shields.io/badge/Plotly-5.4.0-blue)
![glob](https://img.shields.io/badge/glob-3.2.0-lightgrey)
![os](https://img.shields.io/badge/os-Builtin-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-green)
![NiBabel](https://img.shields.io/badge/NiBabel-3.2.1-red)

📂 Dataset

Used BraTS (Brain Tumor Segmentation Challenge) dataset for training & validation.

Includes T1, T2, Flair, and T1c MRI modalities.

🛠 Installation & Setup

Step 1: Clone the repository

git clone https://github.com/your-username/brain-tumor-ai.git
cd brain-tumor-ai

Step 2: Install dependencies

pip install -r requirements.txt

Step 3: Train the AI Model

python train.py  # Trains the U-Net model on BraTS dataset

Step 4: Segment & Visualize Tumor

python predict.py  # Runs segmentation on input MRI

🎥 Demo & Workflow

Upload MRI scan → Model segments tumor regions.

3D reconstruction → Generates tumor & brain model.

Visualization → Helps doctors plan surgical approach.



📊 Results & Performance

Segmentation Accuracy: (Mention Dice Score, IoU, etc.)

Time Taken: Faster than manual segmentation (~X minutes per scan)

🌟 Future Scope

AR/VR integration for interactive 3D tumor visualization.

Cloud-based medical imaging platform for hospitals.

Live tracking during surgery using real-time MRI feeds.







