# iSarcasm
**URL**: [https://github.com/dmbavkar/iSarcasm](https://github.com/dmbavkar/iSarcasm)

**Description**: A Dataset of Intended Sarcasm

## Methods
The **iSarcasm** dataset is designed to detect intended sarcasm in tweets. It contains tweets labeled as sarcastic or non-sarcastic, and the sarcastic tweets are further categorized into different types of ironic speech:

1. **Sarcasm**: Tweets that contradict the state of affairs and are critical towards an addressee.
2. **Irony**: Tweets that contradict the state of affairs but are not obviously critical.
3. **Satire**: Tweets that appear to support an addressee but contain underlying disagreement and mocking.
4. **Understatement**: Tweets that undermine the importance of the state of affairs they refer to.
5. **Overstatement**: Tweets that describe the state of affairs in exaggerated terms.
6. **Rhetorical Question**: Tweets that include a question whose inferred meaning contradicts the state of affairs.

Each sarcastic tweet in the dataset includes:
- An explanation provided by the author as to why the tweet is sarcastic.
- A rephrase of the tweet that conveys the same meaning non-sarcastically.

The dataset includes **4,484 tweets**, with **777** labeled as sarcastic and **3,707** labeled as non-sarcastic.

## Results
The **iSarcasm** dataset has been widely used to evaluate state-of-the-art sarcasm detection models. The dataset provides detailed insights into different types of sarcasm and has been rigorously validated by the authors to reduce noise that may arise from traditional manual labeling methods. 

It has been shown that models trained on this dataset can achieve robust performance in sarcasm detection tasks, accounting for various types of sarcastic expressions.

## Dataset
- **Tweet count**: 4,484 tweets.
- **Sarcastic tweets**: 777.
- **Non-sarcastic tweets**: 3,707.
- The dataset is split into **80% training** and **20% testing**, available in the files `isarcasm_train.csv` and `isarcasm_test.csv`.
- Each record includes:
  - `tweet_id`: Identifier of the tweet.
  - `sarcasm_label`: Label indicating if the tweet is sarcastic or not.
  - `sarcasm_type`: Type of sarcasm (only for sarcastic tweets).
  
This dataset can be used for training sarcasm detection models, and it is distinct in that the labels have been provided by the authors of the tweets themselves, reflecting their intended sarcasm.

The paper detailing the dataset's creation and its applications can be cited as follows:
- **Citation**: Oprea, Silviu, and Magdy, Walid. "iSarcasm: A Dataset of Intended Sarcasm", ACL 2020. 
  [Link to draft](https://arxiv.org/abs/1911.03123).
