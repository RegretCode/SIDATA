# Text-Classification-with-BERT-PyTorch  
**URL**: [https://github.com/mabdullah1994/Text-Classification-with-BERT-PyTorch](https://github.com/mabdullah1994/Text-Classification-with-BERT-PyTorch)  

## Description  
This project implements a text classifier fine-tuned on pre-trained BERT for sarcasm detection in news headlines, utilizing PyTorch. The model leverages transfer learning to detect sarcasm, making use of a pre-trained BERT model and fine-tuning it on a specific sarcasm detection dataset.  

### Kaggle Notebook  
- [Transfer Learning for Text Data in Pytorch (BERT)](https://www.kaggle.com/aaybeedee/transfer-learning-for-text-data-in-pytorch-bert)  

### Dataset  
- [News Headlines Dataset for Sarcasm Detection](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection/)  

### Prerequisites  
- Python 3.7  
- PyTorch 1.1.0  
- pytorch-transformers  
- pandas  
- numpy  
- tqdm  

## Methods  
The model uses **BERT (Bidirectional Encoder Representations from Transformers)**, a pre-trained transformer model, which is fine-tuned specifically for sarcasm detection in news headlines. The fine-tuning process adjusts the pre-trained model for the task at hand by training it on a labeled dataset of sarcastic and non-sarcastic headlines.  

## Results  
- **Epoch 1**: Train Accuracy = 69.89%, Validation Accuracy = 81.16%  
- **Epoch 2**: Train Accuracy = 83.52%, Validation Accuracy = 83.64%  
- **Epoch 3**: Train Accuracy = 87.21%, Validation Accuracy = 82.70%  
- **Epoch 4**: Train Accuracy = 89.38%, Validation Accuracy = 85.23%  
- **Epoch 5**: Train Accuracy = 91.09%, Validation Accuracy = 85.54%  
- **Epoch 6**: Train Accuracy = 92.23%, Validation Accuracy = 85.86%  

## Models  
The model used is a fine-tuned **BERT** for sarcasm detection, with the specific model parameters and configuration available in the repository.
