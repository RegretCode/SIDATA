# ArSarcasm
**URL**: [https://github.com/iabufarha/ArSarcasm](https://github.com/iabufarha/ArSarcasm)

**Description**: This repository contains the Arabic sarcasm dataset (ArSarcasm).

## Project Overview
ArSarcasm is a dataset for sarcasm detection in Arabic tweets. It was built using existing Arabic sentiment analysis datasets (**SemEval 2017** and **ASTD**) and includes annotations for sarcasm and dialect.

## Dataset:
The dataset contains **10,547 tweets**, where **1,682 (16%)** are labeled as sarcastic. The dataset is available in **CSV format** with an **80/20 train-test split**:
- **Training set**: 8,437 tweets
- **Test set**: 2,110 tweets

## Dataset Fields:
- **tweet**: The original tweet text.
- **sarcasm**: Boolean indicating whether the tweet is sarcastic.
- **sentiment**: New annotation for sentiment (positive, negative, neutral).
- **original_sentiment**: Sentiment from the original dataset annotation.
- **source**: The original dataset (SemEval or ASTD).
- **dialect**: The Arabic dialect used in the tweet, categorized into:
  - **msa**: Modern Standard Arabic
  - **egypt**: Egyptian and Sudanese Arabic
  - **levant**: Levantine Arabic (Palestine, Jordan, Syria, Lebanon)
  - **gulf**: Gulf Arabic (Saudi Arabia, UAE, Qatar, etc.)
  - **magreb**: North African Arabic (Algeria, Libya, Tunisia, Morocco)

## Dataset Usage:
The dataset is structured for sarcasm detection research and includes sentiment and dialectal variations, making it useful for broader NLP tasks in Arabic.

## Dataset Statistics:
- **Total tweets**: 10,547
- **Sarcastic tweets**: 1,682 (16%)
- **Train set size**: 8,437
- **Test set size**: 2,110

## Training Methods:
No specific training methods are provided in the repository.

## Results:
No specific results or performance metrics are provided in the repository.

## Dataset Files:
- **ArSarcasm_train.csv** (1.7 MB)
- **ArSarcasm_test.csv** (435 KB)
