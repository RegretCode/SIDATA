# Sarcasm Detection  
**URL**: [https://github.com/MirunaPislar/Sarcasm-Detection](https://github.com/MirunaPislar/Sarcasm-Detection)  

## Description  
This project explores **sarcasm detection on Twitter** using both **traditional machine learning** and **deep learning techniques**. Sarcasm, a form of verbal irony, is challenging to detect in written text due to the absence of paralinguistic cues such as intonation and facial expressions.  

The project was completed as part of a **Bachelor of Science in Computer Science** at the **University of Manchester**, under the supervision of **Mr. John McNaught**. A video summarizing the project achievements is available [here](https://www.youtube.com/watch?v=ofrn3T76dHg).  

## Methods and Models  
The study investigates various methods for sarcasm detection in tweets:  

- **Traditional Machine Learning Models:**  
  - Support Vector Machines (SVMs)  
  - Logistic Regression  
  - Discrete feature-based classifiers  

- **Deep Learning Models:**  
  - Convolutional Neural Networks (CNNs)  
  - Long Short-Term Memory Networks (LSTMs)  
  - Gated Recurrent Units (GRUs)  
  - Bi-directional LSTMs  
  - Attention-based LSTMs  

These models were evaluated on **four different Twitter datasets** (details available in `res/` folder).  

## Datasets  
The repository contains both **raw and processed Twitter datasets**, as well as vocabularies, word lists, and emoji selections that were useful for preprocessing.  

## Implementation Details  
The source code is structured into multiple directories:  
- **`src/`** – Code for data processing, analysis, training, and evaluation.  
- **`res/`** – Datasets and preprocessed resources.  
- **`models/`** – Pre-trained and trained models.  
- **`plots/`** – Visualization plots used to support the results.  
- **`stats/`** – Statistical comparisons between different preprocessing and model evaluation stages.  
- **`images/`** – Model architecture visualizations and screenshots from the project report.  

## Requirements  
The code has been tested on **Python 3.5 (Ubuntu 16.04)** with **Keras 2.0.8** and **TensorFlow 1.3** as the backend.  

Required dependencies:  
- Python 3.5  
- Keras 2.0  
- TensorFlow 1.3  
- gensim 3.0  
- numpy 1.13  
- scikit-learn  
- h5py  
- emoji  
- tqdm  
- pandas  
- itertools  
- matplotlib  

## Results  
The performance of different deep learning models on the considered datasets is summarized in the table below:  

- [Results](https://github.com/MirunaPislar/Sarcasm-Detection/blob/master/README.md#results)  

## Visualizations  
The project includes tools to visualize deep network layers. Running specific scripts generates `.html` files in `plots/html_visualizations/`, which allow detailed analysis of hidden unit activations.  

## Disclaimer  
The primary goal of this project was **not** to develop the most computationally efficient implementation but rather to derive meaningful insights about sarcasm detection in Twitter data. While the code has been reviewed and verified, users should apply it at their own discretion.  
