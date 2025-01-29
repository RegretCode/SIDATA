# sentence-encoder-irony-detection  
**URL**: [https://github.com/rangwani-harsh/sentence-encoder-irony-detection](https://github.com/rangwani-harsh/sentence-encoder-irony-detection)  

## Description  
This repository contains models for irony detection based on the AllenNLP framework. It implements an attention-based model for detecting irony, which was developed as part of the SemEval 2018 Task 3.

### Project Overview  
- **Models**: The repository includes two different attention mechanisms for encoding sentence representations:
  1. Basic Attention Layer (achieved an F1 score of 69.19%).
  2. Structured Self-attentive Sentence Embedding by Lin et al. (achieved an F1 score of 70.00%).
- **Components**: The model consists of three main components:
  - **Reader**: Responsible for reading the dataset from `.txt` files.
  - **Model**: Defines the neural network architecture, which is a sequence-to-sequence encoder followed by a feed-forward network for classification.
  - **Predictor**: Used for running the demo and evaluation process.

### Methodology  
- **Architecture**: The model utilizes attention mechanisms to capture key features in sentences, aiming to detect irony in text.
- **Training**: The model is trained on data from the SemEval 2018 Irony Detection Subtask (Task 3), and performance is evaluated using the F1 score.

### Dataset  
The dataset used for training and testing is from the SemEval 2018 Task 3, which focuses on irony detection. The data is stored in `.txt` files and is processed using the Reader component.

## Results  
- **Basic Attention Layer**: The best performance achieved by this model was an F1 score of 69.19%.
- **Structured Self-attentive Sentence Embedding**: This model achieved a higher performance, with an F1 score of 70.00%.

## Implementation & Code  
The repository includes:
- **Attention Models**: Implementation of basic attention and self-attentive mechanisms.
- **Training & Evaluation**: Scripts to train the models and evaluate their performance using F1 score.
- **Configuration**: Hyperparameters and model configuration are specified in the experiments directory.
