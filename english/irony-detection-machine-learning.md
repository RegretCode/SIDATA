# irony-detection-machine-learning
**URL**: [https://github.com/ShereenMamdouh/irony-detection-machine-learning](https://github.com/ShereenMamdouh/irony-detection-machine-learning)

**Description**: It's a Python code that works on 3 features (bag of words, semantic analysis, and word embedding) and 4 classifiers (SVM, K nearest neighbor, Naive Bayes, and decision trees) to classify tweets as ironic or not, supervised by a Twitter dataset.

## Methods
- **Features Used**:
  - **Bag of Words**: Counts word frequencies in tweets to identify irony.
  - **Semantic Analysis**: Analyzes the sentiment polarity of the tweet, checking for contradictions between sentiments.
  - **Word Embedding**: Converts words into numerical vectors to identify patterns in ironic tweets.
  
- **Classifiers Used**:
  - **Naive Bayes Classifier**: A probabilistic classifier assuming independence between features.
  - **SVM**: A supervised learning algorithm aiming to increase the gap between data to separate two categories.
  - **Random Forest**: An algorithm generating multiple decision trees.
  - **K-Nearest Neighbor (K-NN)**: Classifies tweets based on the k closest data points, with k=1 for best results.
  
- **Text Preprocessing**:
  - **Tokenization**: Splits sentences into words.
  - **Lemmatization**: Reduces words to their root forms.
  - **Stop Words Removal**: Removes irrelevant words to improve performance.
  - **Data Filtering**: Filters out unnecessary information from tweets.
  
## Results
- **Best Accuracy**: 
  - Bag of Words with Naive Bayes classifier yielded the best accuracy.
  - Semantic analysis with K-NN performed best.
  - Word embedding with Decision Trees gave the best performance.
- **Overall Performance**: The best accuracy achieved so far is approximately 70% using Naive Bayes with Bag of Words, given that the problem is mostly defined with 80% ironic tweets.
- **Next Steps**: The project is under implementation for further improving results by using Sentence2Vec, LSTM, and combining all features into one matrix for better classification performance.

## Dataset
- **Dataset Used**: 
  - The dataset used is from **SemEval-2018 Task 3**, consisting of 3842 tweets.
  - **Distribution**: 
    - 604 tweets are classified as **Non-Ironic**.
    - 2396 tweets are classified as **Ironic**.
  - **Format**: 
    - The dataset contains 3 attributes: **Index**, **Class** (Ironic or Non-Ironic), and **Tweet**.
  
- **Data Processing**:
  - The data is processed by splitting the dataset into vectors for **Index**, **Labels**, and **Tweets**.
  - **Text preprocessing** is applied, including filtering stop words, tokenization, and lemmatization, followed by feature extraction (bag of words, sentiment analysis, and word embedding).
