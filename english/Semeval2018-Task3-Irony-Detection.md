# Semeval2018-Task3-Irony-Detection  
**URL**: [https://github.com/zhenduow/Semeval2018-Task3-Irony-Detection](https://github.com/zhenduow/Semeval2018-Task3-Irony-Detection)  

## Description  
This repository implements the solution for the SemEval-2018 Task 3, focusing on irony detection in tweets. The task is divided into two subtasks, and this repository addresses the binary classification subtask (Task A), where the goal is to classify tweets as ironic (1) or non-ironic (0).

### Project Overview  
- The system uses syntactic and affective features, such as sentence semantic similarity, discourse markers, named entity recognition (NER), adjectives/adverbs, punctuation, sentiment polarity, and subjectivity, to classify tweets.
- The baseline models are built using logistic regression, random forest, and support vector machines (SVM), tested using 10-fold cross-validation.
- The repository also includes code for preprocessing and feature extraction.

### Methodology  
- **Preprocessing**: Data cleaning to remove non-syntactic elements such as mentions, hashtags, and URLs. Part-of-speech tagging is used to identify sentence structures.
- **Feature Extraction**: Syntactic features (e.g., sentence semantic similarity, discourse markers, NER) and affective features (e.g., sentiment polarity, subjectivity) are extracted to build a feature matrix.
- **Model Training**: The feature matrix is used to train the classifiers (logistic regression, random forest, SVM).
- **Evaluation**: The classifiers are evaluated using accuracy, precision, recall, and F1-score.

### Dataset  
The training dataset, provided by the task organizers, consists of 3,834 tweets labeled as ironic (1) or non-ironic (0).

## Results  
The models demonstrate good performance, achieving high accuracy, precision, recall, and F1-scores with the extracted features.

## Implementation & Code  
The repository contains scripts for:
- **Preprocessing** (`preProcessing.py`)
- **Feature extraction** (`structuralfeatures.py`, `affectiveFeatures.py`, `sentencesimilarity.py`, etc.)
- **Classifier implementation** (`classifiers.py`)
- **Model evaluation** (`evaluate.py`)