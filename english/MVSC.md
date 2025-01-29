# MVSC
**URL**: [https://github.com/MIND-Lab/MVSC](https://github.com/MIND-Lab/MVSC)

**Description**:  
The Multi-View Sentiment Corpus (MVSC) consists of 3000 tweets, each labeled by three annotators with sentiment, emotion, irony, subjectivity, and implicitness. The dataset is designed to offer a multi-dimensional view of sentiment analysis by considering multiple aspects of language, including emotions, sentiment polarity, and the presence of irony or implicitness.

## Methods
The MVSC corpus is structured to provide a rich set of labels for each tweet, covering different aspects that are crucial for understanding sentiment and irony in text:
1. **Emotion**: Labels include anger, anticipation, joy, trust, fear, surprise, sadness, disgust, and none.
2. **Irony**: Tweets are classified as either ironic or not ironic.
3. **Implicitness/Explicitness**: Classifications into explicit, implicit, or none.
4. **Subjectivity/Objectivity**: Classifications of tweets as either subjective or objective.
5. **Sentiment**: Sentiment polarity is labeled as positive, negative, or neutral.

Each emoji within a tweet, if present, is also annotated with a sentiment polarity (positive, negative, neutral) or topic-relatedness.

### Files
The MVSC corpus includes two tab-separated files:
- **MVSC Tweet Corpus.csv**: Contains tweet text, sentiment, emotion, irony, subjectivity, and implicitness annotations.
- **MVSC Emoji Corpus.csv**: Provides sentiment labels related to emojis used in the tweets.

### Format Example (MVSC Tweet Corpus):
Each entry in the **MVSC Tweet Corpus.csv** includes the following fields:
- **tweet_id**: Numerical ID of the tweet.
- **tweet_text**: The UTF-8 encoded text of the tweet.
- **user_id**: Unique identifier for the user who posted the tweet.
- **keyword**: The keyword used to retrieve the tweet related to two popular movies: *Deadpool* and *Suicide Squad*.
- **Emotion_A1, A2, A3**: Emotion labels for each of the three annotators (anger, anticipation, joy, trust, fear, surprise, sadness, disgust, None).
- **Irony_A1, A2, A3**: Irony labels (Ironic, Not Ironic).
- **Implicit-Explicit_A1, A2, A3**: Labels for implicitness/explicitness (Explicit, Implicit, None).
- **Subjectivity_A1, A2, A3**: Labels for subjectivity/objectivity (Subjective, Objective).
- **Tweet_Sentiment_A1, A2, A3**: Sentiment labels for polarity (Positive, Negative, Neutral).

### Example Format (MVSC Emoji Corpus):
Each entry in the **MVSC Emoji Corpus.csv** includes:
- **tweet_id**: Numerical ID of the tweet.
- **emoji_position**: The position of the emoji in the tweet, ordered by appearance.
- **Tweet_Sentiment_A1, A2, A3**: Sentiment polarity and topic-relatedness labels for the emoji (Topic, Positive, Negative, Neutral).

## Results
As this repository contains the dataset, the results are not directly provided. Researchers can use this multi-annotated dataset to train and evaluate sentiment and sarcasm detection models, with a focus on understanding the interplay between different linguistic dimensions like emotion, sentiment, irony, and subjectivity.

## Dataset
The MVSC dataset includes:
1. **Tweets**: 3000 tweets labeled by 3 annotators across five dimensions: sentiment, emotion, irony, subjectivity, and implicitness.
2. **Emojis**: Labels for emojis used in tweets, considering sentiment and topic-relatedness.

Files included in the repository:
- **MVSC Tweet Corpus.csv**
- **MVSC Emoji Corpus.csv**

You can access the corpus and the raw data from the repository: [MVSC Dataset](https://github.com/MIND-Lab/MVSC)
