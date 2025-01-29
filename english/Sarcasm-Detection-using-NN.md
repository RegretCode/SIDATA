# Sarcasm Detection using Neural Networks  
**URL**: [https://github.com/rishabhmisra/Sarcasm-Detection-using-NN](https://github.com/rishabhmisra/Sarcasm-Detection-using-NN)  

## Description  
This repository is a PyTorch implementation of the work presented in the paper "Modelling Context with User Embeddings for Sarcasm Detection in Social Media" ([paper link](https://arxiv.org/pdf/1607.00976.pdf)). The neural network model uses the tweet content and corresponding user embeddings (context) to classify tweets as sarcastic or non-sarcastic. The repository also includes an improved framework for sarcasm detection using a **Hybrid Neural Network (HNN)** approach ([paper link](https://arxiv.org/abs/1908.07414)).

## Methods and Models  
- **Model Type**: Hybrid Neural Network (HNN)  
- **Model Inputs**:  
  - Tweet content  
  - User embeddings (context)  
- **Approach**:  
  - Original work uses a combination of user embeddings and tweet content to predict sarcasm.
  - The extended version implements the HNN architecture for improved sarcasm detection.
  
## System Requirements  
- Python 2.7  
- PyTorch 0.3.1  
- Python packages:  
  - gensim  
  - yandex.translate  
  - ipdb  

## Instructions for Running the Code  
1. **Pre-requisites**:  
   - Obtain pre-trained word embeddings (e.g., **Skip-gram**) and user embeddings ([user embeddings link](https://github.com/samiroid/CUE-CNN?tab=readme-ov-file)).  
   - Place word embeddings in `DATA/embeddings/` and name the file `words.txt`.  
   - Place user embeddings in `DATA/embeddings/` and name the file `usr2vec.txt`.
   
2. **Running the Code**:  
   - To run the original code:  
     ```bash  
     python train_CUE_CNN.py  
     ```  
   - To run the RNN + CNN Hybrid model on the new dataset:  
     ```bash  
     python Headlines_RNN.py  
     ```  

## Output, Results, and Visualization  
- A `progress` folder is generated with subfolders for each run.  
- Inside each run folder, the following files are generated:  
  - **logs.txt**: Contains loss and accuracy on train/test/validation sets after each epoch.  
  - **stats.jpg**: Plots the train/test/validation loss and accuracy on a single graph.  

### Results  
No explicit results (accuracy, precision, recall, F1-score) are provided in the repository. However, the paper associated with this work may contain evaluation metrics.

## Note  
The utility files, pre-trained user embeddings, and raw tweet IDs were obtained from the [Original CUE-CNN repository](https://github.com/samiroid/CUE-CNN).
