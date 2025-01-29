# tweet-irony-detection  
**URL**: [https://github.com/desh2608/tweet-irony-detection](https://github.com/desh2608/tweet-irony-detection)  

## Description  
This project provides a model for irony detection in tweets, specifically developed for the **SemEval 2018 Task 3**. The model uses a combination of feature generation techniques and classification models to detect irony in tweet text.

## Methods  
### Feature Generation  
The model generates features from two different sources:
1. **Holographic Embeddings**: This method uses circular cross-correlation between tweet text and hashtag vectors. The feature generation script can be found in the `holographic.ipynb` file.
2. **DeepMoji**: This feature generation method uses a pre-trained emoji prediction model that has been forked and modified to support Python 3.5+. The script for generating features is located in `deepmoji_features.ipynb` and must be placed in the `DeepMoji/examples` directory.

### Classification  
After feature generation, the **XGBoost** classifier is employed to classify the generated features. The classification process is implemented in the `xgb_classifier.ipynb` file.  

## Results  
No specific results or performance metrics are provided in the repository.

## Models  
The model used in this project is based on **XGBoost**, a popular gradient boosting algorithm. It is trained using the features generated from the **Holographic embeddings** and **DeepMoji** methods.

## Dataset  
The model relies on tweet data, but the repository does not provide any specific dataset. Users are instructed to use their own data or refer to the **SemEval 2018 Task 3 dataset** for irony detection.
