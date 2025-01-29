# dataset-pruning-sarcasm-detection
**URL**: [https://github.com/priyank96/dataset-pruning-sarcasm-detection](https://github.com/priyank96/dataset-pruning-sarcasm-detection)

**Description**: No description provided.

## Project Overview
This repository focuses on **fine-tuning models for sarcasm detection** using a **pruned dataset**.

## Training Methods:
- The repository includes several **pre-trained models**:
  - RoBERTa
  - XLNet
  - Electra
- The models can be executed by running:
  ```bash
  python ./Models/model-name/model-name.py
  ```
- Dependencies are installed via:
  ```bash
  pip install -r requirements.txt
  ```
- The dataset used for training is **SARC** (*Sarcastic Comments on Reddit*), which can be downloaded from:
  - [Kaggle Dataset](https://www.kaggle.com/datasets/sherinclaudia/sarcastic-comments-on-reddit).

## Results:
- The best results from the paper can be reproduced by running:
  ```bash
  python ./Models/RoBERTa/RoBERTa.py
  ```
- The repository is based on a fork of **SemEval 2022 Task 6 - Sarcasm Detection** ([GitHub](https://github.com/AmirAbaskohi/SemEval2022-Task6-Sarcasm-Detection)).
- More details on the approach can be found in their related paper:  
  [SemEval-2022 Task 6 Paper](https://arxiv.org/pdf/2204.08198.pdf).

## Dataset:
- **Source**: Kaggle (SARC dataset).
- **File**: `train-balanced-sarcasm.csv` (not included in the repository but can be downloaded separately).
