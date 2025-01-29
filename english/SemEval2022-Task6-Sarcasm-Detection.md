# SemEval2022-Task6-Sarcasm-Detection  
**URL**: [https://github.com/AmirAbaskohi/SemEval2022-Task6-Sarcasm-Detection](https://github.com/AmirAbaskohi/SemEval2022-Task6-Sarcasm-Detection)  

## Description  
Sarcasm is commonly used on social media to mock, irritate, or amuse others. Its metaphorical nature poses significant challenges for sentiment analysis systems. This repository presents the results of the UTNLP team in the SemEval-2022 Task 6 on sarcasm detection, including a comparative analysis of various models and data augmentation techniques. The study compares machine learning models, transformer-based models, and data augmentation strategies, including both generative-based and mutation-based methods. The best approach achieved an F1-score of 0.414 after refining the initial model.

### Project Overview  
- **Data**: The main dataset used in this study is the iSarcasm dataset, with additional datasets such as Sarcasm Headlines, Sentiment140, and Twitter News used for data augmentation. A mutated version of the main dataset is also used.
- **Models**: The repository includes various models such as XLNet, Electra, RoBERTa, GPT-2, and BERT-based models, alongside other machine learning models like SVM and LSTM.
- **Data Augmentation**: Two strategies are used—generative data augmentation using GPT-2 and mutation-based augmentation with shuffling, synonym replacement, and word elimination. The best results were obtained with a combination of mutation-based augmentation and RoBERTa.

### Methodology  
- **Data Preprocessing**: Various techniques such as stemming, lemmatization, and link removal were tested to process the data for model input.
- **Data Augmentation**: The dataset is augmented using mutation methods (shuffling, elimination, and synonym replacement) and generative models (GPT-2). Several combinations of these methods were tested to find the optimal setup.
- **Model Training**: Several models, including transformer-based and attention-based models, were trained and evaluated on the augmented datasets.

### Dataset  
- **Main Dataset**: The task-specific dataset provided by SemEval-2022.
- **Secondary Datasets**: Sarcasm Headlines Dataset, Sentiment 140, SPIRS, and others were used for data augmentation.
- **Mutated Dataset**: The dataset with mutation-based modifications such as word elimination, synonym replacement, and shuffling.
- **File Structure**: The data is organized into the following directories:
  - `Cleaned Dataset/`: The preprocessed main dataset.
  - `Foreign Dataset/`: Secondary datasets like Sentiment 140.
  - `Main Dataset/`: The task-specific training dataset.
  - `Mutant Dataset/`: The mutated version of the main dataset.
  - `Train_Dataset.csv` and `Test_Dataset.csv`: Combined datasets for training and testing.

## Results  
The models were evaluated using F1-score and accuracy, with the following results:

| Data Augmentation           | F1-Score | Accuracy |
|-----------------------------|----------|----------|
| Shuffling                   | 0.305    | 0.7471   |
| Shuffling + Replacing       | 0.3011   | 0.7414   |
| Shuffling + Elimination     | 0.3064   | 0.7478   |
| Elimination                 | 0.301    | 0.7478   |
| GPT-2                       | 0.2923   | 0.675    |

| Model                       | F1-Score | Accuracy |
|-----------------------------|----------|----------|
| SVM                         | 0.3064   | 0.7478   |
| LSTM-based                  | 0.2751   | 0.7251   |
| BERT-based                  | 0.414    | 0.8634   |
| Attention-based             | 0.2959   | 0.7793   |
| Google’s T5                 | 0.4038   | 0.8124   |
| Electra                     | 0.2907   | 0.7642   |

## Implementation & Code  
The repository contains scripts for:
- **Data Augmentation**: Including GPT-2 and mutation-based augmentation techniques.
- **Preprocessing**: Different methods like stemming and lemmatization.
- **Model Training**: Implementations of various models, including transformer-based (RoBERTa, BERT, XLNet) and machine learning models (SVM, LSTM).
- **Evaluation**: Scripts for evaluating the models using F1-score and accuracy.
