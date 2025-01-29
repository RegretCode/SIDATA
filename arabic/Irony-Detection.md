# Irony-Detection
**URL**: [https://github.com/TharinduDR/Irony-Detection](https://github.com/TharinduDR/Irony-Detection)

**Description**: This repository contains the work submitted for the IDAT 2019 Shared Task — detecting irony in Arabic tweets by RGCL.

## Dataset
- **Name**: IDAT 2019 Dataset
- **Size**:
  - Arabic:
    - Training data: 798 KB
  - English:
    - Labels test set: 8.4 KB
    - Offenseval training data: 1.87 MB
    - Test set: 130 KB

## Additional Information

### How the datasets were created
The dataset used in this project was part of the **IDAT 2019 Shared Task**, the first shared task focused on irony detection in Arabic tweets.  
- **Task**: Classify tweets as either **ironic** or **not ironic**.  
The dataset includes both Arabic and English components, with specific subsets for training, testing, and label annotations.

### Training methods applied
Several models were implemented for the task, including:
- **Capsule Networks**: Achieved the highest performance, with an F1-score of **0.798**.
- **CNN (Convolutional Neural Networks)**: Closely followed, with an F1-score of **0.800**.
- **Pooled GRU (Gated Recurrent Units)**: Scored an F1 of **0.785**.
- **Attention LSTM (Long Short-Term Memory)**: Achieved an F1 of **0.760**.
- **Attention LSTM GRU**: Reached an F1 of **0.762**.
- **Attention Capsule**: Scored an F1 of **0.764**.

### Results obtained
Below is a summary of the results achieved by the models on the IDAT 2019 dataset:

| Model              | Precision | Recall | F1     |
|--------------------|-----------|--------|--------|
| **Capsule**        | 0.807     | 0.800  | 0.798  |
| **CNN**            | 0.806     | 0.801  | 0.800  |
| **Pooled GRU**     | 0.800     | 0.789  | 0.785  |
| **Attention LSTM** | 0.788     | 0.766  | 0.760  |
| **Attention LSTM GRU** | 0.783 | 0.768  | 0.762  |
| **Attention Capsule**  | 0.776 | 0.768  | 0.764  |

The **Capsule Network** and **CNN** models were the most effective for the task.