# Automatic Sarcasm Detection  
**URL**: [https://github.com/EducationalTestingService/sarcasm](https://github.com/EducationalTestingService/sarcasm)  

## Description  
This repository contains datasets and research materials related to **sarcasm detection**, including data from the **2nd FigLang Workshop at ACL 2020**. It provides **shared tasks** and benchmarks for sarcasm detection in **Twitter and Reddit** conversations.  

## Dataset  
The repository includes training and testing datasets for sarcasm detection in **Twitter and Reddit**, provided in **JSONL format**.  

### Data Format  
Each entry in the dataset contains:  
- **label**: `"SARCASM"` or `"NOT_SARCASM"`  
- **id**: Unique identifier for each sample (used for submission tracking)  
- **response**: The sarcastic **Tweet** or **Reddit post**  
- **context**: Ordered **conversation context**, where each message is a reply to the previous one  

### Dataset Statistics  
| Platform | Train Size | Test Size |  
|----------|-----------|----------|  
| **Reddit**  | 4,400  | 1,800  |  
| **Twitter** | 5,000  | 1,800  |  

### Shared Task & Evaluation  
- Participants were provided with **training data (response + context + label)**.  
- **Test data** included the **response** and **context**, but without the label.  
- Submissions had to predict **sarcasm labels** for the test samples.  

## References  
**Main Paper**:  
- *A Report on the 2020 Sarcasm Detection Shared Task*  
  - **Debanjan Ghosh, Avijit Vajpyee, Smaranda Muresan**  
  - *Proceedings of the Second Workshop on Figurative Language Processing*  

## Ethical Considerations  
**Potentially Controversial Content**:  
- The dataset is **collected from social media**, so it may contain **informal, politically charged, or controversial** discussions.  
- The training data has been **lightly pre-processed** to remove offensive content, but **some sensitive material may still be present**.  

## Implementation & Results  
- No specific **model implementations** are included in this repository.  
- There are no **pre-trained models, evaluation metrics, or performance benchmarks**.  
