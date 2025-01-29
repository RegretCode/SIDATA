# Intended-Sarcasm-Detection-In-English-and-Arabic-for-extremly-unbalanced-datasets
**URL**: [https://github.com/rematchka/Intended-Sarcasm-Detection-In-English-and-Arabic-for-extremly-unbalanced-datasets](https://github.com/rematchka/Intended-Sarcasm-Detection-In-English-and-Arabic-for-extremly-unbalanced-datasets)

**Description**: This repo contains work carried out for SemEval 2022 Task 6: iSarcasmEval: Intended Sarcasm Detection In English and Arabic.

## Methods
The repository includes the implementation of the system used in **SemEval-2022 Task 6: Intended Sarcasm Detection in English and Arabic**. The proposed approach involves the following steps:
1. **Voting Classifier**: A classifier combining multiple BERT-based models (KimCNN) to improve performance on an extremely unbalanced dataset.
2. **Modified Loss Functions**: The model trains BERT-Base models with customized loss functions designed to address issues associated with unbalanced datasets.
3. **Handcrafted Features**: Features are handcrafted and combined with machine learning models like SVM to improve detection performance.

Additionally, the repository investigates the importance of different layers in BERT-Base models and identifies appropriate loss functions to optimize deep learning models for the unbalanced data scenario.

## Results
- **SemEval-2022 Task 6 Performance**:
  - **Task A**: 20th place (F1-Sarcastic score of 34% and 47%)
  - **Task B**: 16th place (F1-macro score of 0.0560)
  - **Task C**: 10th place (72% accuracy) and 6th place (80% accuracy) on the leaderboard.

The proposed model demonstrated competitive performance by utilizing a voting classifier and addressing the challenges posed by an unbalanced dataset through the use of modified loss functions and ensemble methods.

## Dataset
The dataset used in this work is part of **SemEval-2022 Task 6** and can be accessed via the following repository:
- **Dataset Link**: [iSarcasmEval Dataset](https://github.com/iabufarha/iSarcasmEval)

This dataset includes English and Arabic data for the task of detecting intended sarcasm in text. You can find the detailed instructions for dataset usage and format in the repository.
