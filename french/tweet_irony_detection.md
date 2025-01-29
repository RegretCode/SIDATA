# tweet_irony_detection
**URL**: [https://github.com/paihengxu/tweet_irony_detection](https://github.com/paihengxu/tweet_irony_detection)

**Description**: Course project for CS666.

## Dataset Creation
The dataset used in this repository is sourced from **SemEval-2018 Task 3**, which involves sarcasm and irony detection in tweets. Tweets were collected using the **Twitter API** with hashtags like #irony, #sarcasm, and #not. The corpus contains a total of **4,792 tweets** which are split into:
- **Training set** (80%)
- **Testing set** (20%)

The corpus includes two tasks:
- **Task A**: Binary classification for irony detection (0 for non-ironic, 1 for ironic).
- **Task B**: Multiclass classification with labels for various types of irony (1 for irony by clash, 2 for situational irony, 3 for other irony, and 0 for non-ironic).

Prior to annotation, the corpus was cleaned by removing:
- Retweets
- Duplicates
- Non-English tweets
- Emoji were converted into UTF-8 descriptions (e.g., ":smiling_face:").

## Training Methods
Several feature generation techniques were used for training models:
1. **Feature Generation**:
   - Baseline features were created.
   - Behavior-based features were generated.
   - Word embeddings like **BERT**, **ELMo**, **Skip-gram**, and **CBOW** were used for word representation.

2. **Classification Models**:
   - Logistic Regression (LR) and **Multilayer Perceptron (MLP)** were used for training.
   - Various combinations of features were experimented with, such as:
     - Baseline + Logistic Regression
     - Behavior + Logistic Regression
     - Word embeddings + Logistic Regression
     - Fine-tuned BERT + Logistic Regression

3. **Fine-Tuning BERT**: 
   - The **BERT model** was fine-tuned for better tweet classification using the preprocessed dataset.
   - The fine-tuned BERT model was combined with other features for improved performance.

## Results
- **Task A (Binary)**:
  - Labels: 0 (non-ironic), 1 (ironic).
  - Dataset size: 4,792 tweets with an 80% training and 20% testing split.
  
- **Task B (Multiclass)**:
  - Labels: 1 (irony by clash), 2 (situational irony), 3 (other irony), 0 (non-ironic).
  - The dataset also includes additional emoji information.
  
- **Classification Models**:
  - Performance metrics for individual combinations of features are available, but specific results (accuracy, F1-score, etc.) would depend on model execution with the provided scripts.

### Dataset Files:
- **Training Data**:
  - SemEval2018-T3-train-taskA.txt (size: 372 KB)
  - SemEval2018-T3-train-taskA_emoji.txt (size: 359 KB)
  - SemEval2018-T3-train-taskB.txt (size: 372 KB)
  - SemEval2018-T3-train-taskB_emoji.txt (size: 359 KB)

- **Testing Data**:
  - SemEval2018-T3_input_test_taskA.txt (size: 76.7 KB)
  - SemEval2018-T3_input_test_taskA_emoji.txt (size: 73.8 KB)
  - SemEval2018-T3_input_test_taskB.txt (size: 76.7 KB)
  - SemEval2018-T3_input_test_taskB_emoji.txt (size: 74.7 KB)
