# News-Headlines-Dataset-For-Sarcasm-Detection
**URL**: [https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection](https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection)

**Description**:  
This is a high-quality dataset for the task of Sarcasm Detection. It is collected from two major news websites, **TheOnion** (for sarcastic headlines) and **HuffPost** (for non-sarcastic headlines), and aims to provide better quality data for sarcasm detection compared to noisy Twitter datasets.

## Methods
The dataset is collected from two sources:
- **TheOnion**: Known for publishing sarcastic headlines.
- **HuffPost**: Provides real (non-sarcastic) news headlines.
  
By using formal language and self-contained headlines, the dataset avoids issues present in Twitter-based datasets, such as noisy labels and lack of context in replies.

## Results
- The dataset contains **28,619 records** in total.
- There are **13,635 sarcastic records** and **14,984 non-sarcastic records**.
- Compared to Twitter datasets, it has a significantly lower percentage of pre-trained word embeddings not available (23.35% for this dataset, 35.53% for the Semeval dataset).

## Dataset
- **is_sarcastic**: 1 if the record is sarcastic, otherwise 0.
- **headline**: The headline of the news article.
- **article_link**: Link to the original news article, useful for collecting supplementary data.

### Statistics
| Statistic/Dataset                              | Headlines | Semeval |
|------------------------------------------------|-----------|---------|
| # Records                                      | 28,619    | 3,000   |
| # Sarcastic records                            | 13,635    | 2,396   |
| # Non-sarcastic records                        | 14,984    | 604     |
| % of pre-trained word embeddings not available | 23.35     | 35.53   |

### WordClouds
Word clouds are provided to visually explore the most frequent terms used in sarcastic vs. non-sarcastic headlines.

## Acknowledgements
This dataset was collected from [TheOnion](https://theonion.com) and [HuffPost](https://www.huffingtonpost.com/).
