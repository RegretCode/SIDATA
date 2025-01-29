# frnn_emotion_detection
**URL**: [https://github.com/olha-kaminska/frnn_emotion_detection](https://github.com/olha-kaminska/frnn_emotion_detection)

**Description**: Code for 3 papers: 1) "Fuzzy-Rough Nearest Neighbour Approaches for Emotion Detection in Tweets"; 2) "LT3 at SemEval-2022 Task 6: Fuzzy-Rough Nearest neighbor Classification for Sarcasm Detection"; 3) "Fuzzy Rough Nearest Neighbour Methods for Detecting Emotions, Hate Speech and Irony" by O. Kaminska, Ch. Cornelis and V. Hoste.

## Overview
This repository contains the implementation for multiple papers focused on fuzzy-rough nearest neighbor approaches applied to emotion, sarcasm, and irony detection. The repository includes code for different classifiers and embedding methods used for these tasks, particularly in the context of emotion detection in tweets.

## Methods
The method uses **Fuzzy-Rough Nearest Neighbour (FRNN)** classification with ordered weighted average (OWA) operators, enhanced by text embeddings. The approach aims to detect **emotion intensity** in tweets, as well as perform **sarcasm detection**. The method applies fuzzy-rough sets, which are suited for dealing with the uncertainty and vagueness inherent in textual data, such as social media posts. The FRNN classifier is tuned using different embedding methods and trained on datasets like **SemEval 2018 Task 1** for emotion detection.

Key functions include:
- **Data Preprocessing**: Involves cleaning and preparing the dataset.
- **FRNN-OWA Approach**: Classifying the data using the FRNN algorithm enhanced with OWA operators.
- **Tweets Embedding**: Embedding the tweets using different methods to capture the textual features more effectively.

## Results
The **FRNN-OWA** approach demonstrates competitive performance with the best solutions from the **SemEval 2018 Task 1** (Affect in Tweets) competition, particularly for the **Emotion Intensity (EI-oc)** subtask. The results are comparable to more complex deep learning methods in terms of accuracy, showing the effectiveness of fuzzy-rough classification techniques for emotion and sarcasm detection.

For detailed results and comparisons, the repository refers to the original paper:
- **Fuzzy-Rough Nearest Neighbour Approaches for Emotion Detection in Tweets** presented at **IJCRS 2021** and discussed in **Arxiv**: [Link to Paper](https://arxiv.org/abs/2107.05392).
