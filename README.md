
# EEG Classification using Transformer-GCN Hybrid Model (TensorFlow)

This repository contains a Google Colab notebook implementing a hybrid deep learning architecture combining Transformers and Graph Convolutional Networks (GCN) for EEG signal classification.

## 📁 File
- `GCNTrans_tensorflowfinal_29may.ipynb`: Colab notebook implementing the EEG classification pipeline using TensorFlow.

## 🧠 Description
The model is designed for classifying EEG signals, integrating both spatial and temporal patterns. It leverages:
- Transformer layers for temporal sequence modeling
- GCN layers for capturing spatial dependencies between EEG channels

The project includes:
- Data loading and preprocessing
- Model architecture definition (GCN + Transformer)
- Training and evaluation
- Performance metrics visualization

## 🚀 Run in Google Colab
You can open and run the notebook directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zeynali72/GCN_Transformer/blob/main/GCNTrans.ipynb)

## ⚙️ Requirements
- Python 3.x
- TensorFlow
- NumPy, Pandas
- Scikit-learn
- NetworkX (if graph operations are used)
- Matplotlib / Seaborn (for visualization)

## 📌 Notes
- This notebook was developed and tested in **Google Colab**.
- Data should be placed in the appropriate format; currently assumed to be preprocessed EEG features in numpy or compatible format.

## 📩 Data Access
To receive the required data files, please contact me via email: **z.mahsa.zeynali@gmail.com**

## 👩‍💻 Author
Mahsa Zeynali  
Contact: z.mahsa.zeynali@gmail.com
