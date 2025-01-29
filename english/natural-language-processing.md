# natural-language-processing
**URL**: [https://github.com/deybvagm/natural-language-processing](https://github.com/deybvagm/natural-language-processing)

**Description**:  
This repository demonstrates different NLP models applied to several datasets, including IMDB, YELP, Sentiment140, and Sarcasm. The repository compares various neural network architectures and libraries to solve sentiment classification and text generation tasks, ranging from simple neural networks to advanced models like LSTM, GRU, and CNN.

## Methods
The repository implements and compares different neural network architectures and techniques to handle sentiment classification and text generation tasks:
- **Neural Network Architectures**: Models include simple neural networks, LSTM, GRU, and CNN, with and without regularization techniques.
- **Frameworks**: 
  - [Tensorflow 2.0](https://www.tensorflow.org/)
  - [FastText](https://fasttext.cc/)
- **Hyperparameter Configuration**: The repository allows for comparison of different configurations, evaluating model performance on multiple datasets.

## Results
The repository compares the performance of these architectures on several datasets, highlighting their effectiveness for sentiment analysis and sarcasm detection. Specific results are not provided in the description but can be observed by running experiments on the models provided in the repository.

## Dataset
The repository works with the following datasets:
- **IMDB movie review**: A dataset containing 50,000 movie reviews labeled with binary sentiment polarity (positive or negative). It is split into 25,000 training reviews and 25,000 testing reviews. Available from the TensorFlow data services module.
- **YELP**: Contains 4.7 million reviews from different service providers, such as restaurants and parking lots. The classification task is to predict the star rating (0-5) for each review.
- **Sarcasm**: A dataset with 26,000 sentences labeled as sarcastic or not. The task is to identify sarcasm in text.
- **Sentiment140**: A dataset with 1.6 million tweets, each annotated as either 0 (negative) or 4 (positive) for sentiment classification.
