# Sarcasm Detection with BERT and GCN  
**URL**: [https://github.com/abhilashmnair/Sarcasm-Detection-with-BERT-and-GCN](https://github.com/abhilashmnair/Sarcasm-Detection-with-BERT-and-GCN)  

## Description  
This repository implements a sarcasm detection model using **Bidirectional Encoder Representations for Transformers (BERT)** and **Graph Convolutional Networks (GCN)**. The proposed approach has demonstrated **state-of-the-art performance** compared to traditional models and standard transformer-based techniques.

The repository is associated with the following paper:  
**[Sarcasm Detection using Bidirectional Encoder Representations from Transformers and Graph Convolutional Network](https://www.sciencedirect.com/science/article/pii/S1877050922024991)**  
Presented at the **International Conference on Machine Learning and Data Mining (ICMLDE), 2022**  
Authors: Anuraj Mohan, Abhilash M Nair, Bhadra Jayakumar, Sanjay Muraleedharan  

## Methods and Models  
- **Model Type**:  
  - **BERT-based Transformer**  
  - **Graph Convolutional Network (GCN)**  
- **Key Features**:  
  - Uses **pre-trained BERT embeddings** to enhance context understanding.  
  - Employs **GCNs** to capture relationships between words and their structural dependencies.  
  - Outperforms conventional sarcasm detection models.  

## Datasets  
The model is trained and evaluated on two well-known sarcasm detection datasets:  

| Corpus    | Train Set (Sarcastic) | Train Set (Non-sarcastic) | Test Set (Sarcastic) | Test Set (Non-sarcastic) |
|-----------|----------------------|--------------------------|----------------------|--------------------------|
| **riloff**  | 215                  | 1,153                    | 93                   | 495                      |
| **headlines** | 2,516                | 2,504                    | 570                  | 410                      |

- **riloff dataset**: Collected by **Ellen Riloff**, consists of sarcastic and non-sarcastic tweets.  
  - Available on the [publications page](http://www.cs.utah.edu/~riloff/publications_chron.html).  
  - Some tweets are outdated or removed since their collection in 2013.  
- **headlines dataset**: Collected by **Rishab Misra**, contains news headlines.  
  - Available on [Kaggle](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection).  
  - Sarcastic headlines from **The Onion**, non-sarcastic from **HuffPost**.  

📌 **Note**: These datasets are provided for convenience. Users should ensure they follow the original license and cite the authors accordingly.  

## Requirements  
- `numpy`  
- `spacy`  
- `torch`  
- `scikit-learn`  
- `matplotlib`  
- `pytorch-pretrained-bert`  

## Results  
The repository states that the **BERT + GCN model achieves state-of-the-art performance** against previous approaches. However, **specific accuracy, precision, recall, or F1-score values are not provided** in the documentation. The referenced paper likely contains detailed evaluation metrics.  
