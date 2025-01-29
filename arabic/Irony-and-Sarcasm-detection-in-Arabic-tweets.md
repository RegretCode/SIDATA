# Irony-and-Sarcasm-detection-in-Arabic-tweets
**URL**: [https://github.com/rematchka/Irony-and-Sarcasm-detection-in-Arabic-tweets](https://github.com/rematchka/Irony-and-Sarcasm-detection-in-Arabic-tweets)

**Description**: This repository represents the model developed for irony and sentiment detection in Arabic tweets as part of the WANLP shared tasks on sarcasm and sentiment detection in Arabic tweets.

## Dataset
- **Name**: ArSarcasm
- **Size**: 
  - Training data: 1.7 MB
  - Testing data: 435 KB

## Additional Information

### How the datasets were created
This project used the **ArSarcasm-v2 dataset** (Abu Farha et al., 2021) for the tasks of sarcasm and sentiment detection. The dataset consists of Arabic tweets, manually annotated for sarcasm, sentiment, and dialect. It was originally created to support shared tasks at **WANLP 2021**.

### Training methods applied
The main models implemented include:
- **Multi-headed-LSTM-CNN-GRU**: Combines Long Short-Term Memory (LSTM), Convolutional Neural Networks (CNN), and Gated Recurrent Units (GRU). Preprocessed text and emoji features from tweets were utilized for training.
- **MARBERT**: A transformer-based model designed for Arabic text processing, achieving strong performance on the tasks.

Experiments with these models showed that:
- The **Multi-headed CNN-LSTM-GRU** model ranked **10th out of 27** for sarcasm detection, achieving an F1-Sarcasm score of **0.5662**.
- The **MARBERT-based model** ranked **3rd out of 22** for sentiment detection, achieving an F1-PN score of **0.7321**.

### Results obtained
- **Sarcasm Detection (Task One)**: Achieved an F1-Sarcasm score of **0.5662** (10th place out of 27 submissions).
- **Sentiment Detection (Task Two)**: Achieved an F1-PN score of **0.7321** (3rd place out of 22 submissions).
