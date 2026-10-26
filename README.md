#  Eye-Tracking & Deep Learning for ASD Detection

This repository contains the code and documentation for my Bachelor's Degree Thesis in Medical Systems Engineering: **"Artificial Intelligence to support the diagnosis of Autism Spectrum Disorder"**.

##  Project Overview
The diagnosis of Autism Spectrum Disorder (ASD) is a complex process that relies heavily on clinical observation. This project aims to provide a quantitative, data-driven support tool by applying Deep Learning techniques to eye-tracking data. 

By analyzing the visual trajectories of pediatric patients (ASD vs. Typically Developing), a **Bidirectional Long Short-Term Memory (BiLSTM)** network was developed to classify and detect subtle differences in visual behavior.

##  Dataset
The dataset used in this study consists of eye-tracking recordings from 59 pediatric patients (29 with ASD and 30 neurotypical). 
* The original dataset is publicly available on Kaggle: [Eye-Tracking Dataset to Support ASD Research](https://www.kaggle.com/datasets/imtkaggleteam/eye-tracking-autism).
* **Note:** To run the notebook locally, download the Kaggle dataset and place the CSV files inside a `data/` folder in the root directory.

##  Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy, scikit-learn (StandardScaler, LabelEncoder)
* **Deep Learning Framework:** TensorFlow / Keras
* **Model Architecture:** BiLSTM (Bidirectional LSTM) with Dropout and Batch Normalization.

##  Results
The BiLSTM model significantly outperformed the preliminary Multi-Layer Perceptron (MLP) baseline, achieving excellent balance between sensitivity and specificity:
* **Accuracy:** 92%
* **AUC (Area Under the ROC Curve):** 0.96
* **Recall (ASD Class):** 0.94

##  Full Thesis Documentation
The complete theoretical background, methodology, and detailed discussion of the results are available in the full thesis document (in Italian):
* 📂 [Read the Full Thesis (PDF)](./docs/Tesi_Galetta_Aaron.pdf)
