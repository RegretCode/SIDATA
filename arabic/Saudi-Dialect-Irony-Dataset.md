# Saudi-Dialect-Irony-Dataset
**URL**: [https://github.com/iwan-rg/Saudi-Dialect-Irony-Dataset](https://github.com/iwan-rg/Saudi-Dialect-Irony-Dataset)

**Description**: The Saudi irony dataset was collected using the Twitter API and consists of 19,810 tweets, 8,089 of them are labeled as ironic tweets.

## Dataset
- **Name**: Saudi Dialect Irony Dataset (Sa`7r ساخر)
- **Size**: 19,810 tweets
  - 8,089 ironic tweets
- **File**:
  - `SaudiIrony.csv`: Contains tweets with two labels: "ironic" and "non-ironic" (3.1 MB).

## Additional Information

### How the datasets were created
The Saudi irony dataset (Sa`7r ساخر) was collected using the **Twitter API**. It consists of 19,810 tweets, out of which 8,089 are labeled as ironic. This dataset was created as part of a study on irony detection in sentiment analysis.

### Training methods applied
The dataset was used to train several machine learning models for irony detection:
- **Machine learning models**:
  - K-Nearest Neighbor (KNN)
  - Logistic Regression (LR)
  - Support Vector Machine (SVM)
  - Naïve Bayes (NB)
- **Deep learning models**:
  - BiLSTM
  - AraBERT

### Results obtained
- **SVM** achieved the highest accuracy among the machine learning models with an accuracy of **0.68**.
- **BiLSTM** achieved an accuracy of **0.66**.
- **AraBERT** achieved the highest accuracy overall with **0.71** for detecting irony phrases in Saudi Dialect.

[Read the full paper](https://aclanthology.org/2022.osact-1.7.pdf).