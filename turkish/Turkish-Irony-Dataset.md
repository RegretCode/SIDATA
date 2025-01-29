# Turkish-Irony-Dataset
**URL**: [https://github.com/teghub/Turkish-Irony-Dataset](https://github.com/teghub/Turkish-Irony-Dataset)

**Description**: Turkish Social Media Dataset for Irony Detection

## Project Overview
The Turkish-Irony-Dataset is a dataset designed for irony detection in Turkish social media texts. The dataset consists of 220 Turkish microblog texts, divided equally between ironic and non-ironic sentences. This dataset is particularly valuable for training models to identify irony in informal Turkish text from social media platforms.

## Dataset Details:
- The dataset contains two `.txt` files:
  - **ironic.txt**: Contains 110 ironic sentences. The first 101 lines are in lexicographical order and do not contain emojis or emoticons. The remaining 9 lines contain emojis or emoticons and are not specifically ordered.
  - **non-ironic.txt**: Contains 110 non-ironic sentences. The first 99 lines are in lexicographical order and do not contain emojis or emoticons. The remaining 11 lines contain emojis or emoticons and are not specifically ordered.

## Dataset Usage:
This dataset can be used to train and evaluate models that aim to detect irony in Turkish social media posts.

## Datasets:
- **0_test.tsv** - 1.71 KB
- **0_train.tsv** - 15.6 KB
- **1_test.tsv** - 1.47 KB
- **1_train.tsv** - 15.9 KB
- **2_test.tsv** - 1.57 KB
- **2_train.tsv** - 15.8 KB
- **3_test.tsv** - 1.67 KB
- **3_train.tsv** - 15.6 KB
- **4_test.tsv** - 1.76 KB
- **4_train.tsv** - 15.6 KB
- **5_test.tsv** - 1.71 KB
- **5_train.tsv** - 15.6 KB
- **6_test.tsv** - 1.85 KB
- **6_train.tsv** - 15.5 KB
- **7_test.tsv** - 1.82 KB
- **7_train.tsv** - 15.5 KB
- **8_test.tsv** - 1.78 KB
- **8_train.tsv** - 15.5 KB
- **9_test.tsv** - 1.83 KB
- **9_train.tsv** - 15.5 KB
- **10-fold.csv** - 17.3 KB

## Dataset Statistics:
- **Total sentences**: 220
  - **Ironic sentences**: 110
  - **Non-ironic sentences**: 110
- **Data characteristics**: 
  - Sentences with and without emojis or emoticons.
  - Texts from Turkish social media portals.

## Training Methods:
The dataset requires preprocessing before training. The following steps are involved:
1. **Data Preparation**: Execute the `data_prep.py` script to convert the `.csv` file into `.tsv` format.
2. **Model Execution**: After preparing the data, run the `run_model.py` script to evaluate your model.
3. **Cross-validation**: The dataset includes 10-fold cross-validation files (e.g., `0_train.tsv`, `1_test.tsv`) for evaluating the model's performance.

## Results:
The evaluation results, including accuracy and other metrics, are saved in the `outputs` directory. However, specific performance metrics such as accuracy, precision, recall, or F1 scores were not provided in the information shared.
