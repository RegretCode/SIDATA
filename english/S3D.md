# S3D
**URL**: [https://github.com/surrey-nlp/S3D](https://github.com/surrey-nlp/S3D)  

**Description**:  
This repository contains sarcasm-annotated datasets along with notebooks to use fine-tuned language models. The work was presented at the EMNLP 2022 workshop: *"Utilizing Weak Supervision to Create S3D: A Sarcasm Annotated Dataset."*

## Datasets

The repository provides three datasets focused on sarcasm detection in Twitter data:

- **SAD**: Contains Tweet IDs and sarcasm labels for 2,340 manually annotated tweets collected using the #sarcasm hashtag.  
  - Size: **50.3 KB**  
  - [Available on HuggingFace](https://huggingface.co/datasets/surrey-nlp/SAD)  

- **S3D-v1**: Contains Tweet IDs for 100,000 tweets labeled automatically by a fine-tuned *BERTweet* model. This model was trained on a corpus of over 1 million tweets and Reddit comments labeled for sarcasm in previous studies.  
  - Size: **2.1 MB**  
  - [Available on HuggingFace](https://huggingface.co/datasets/surrey-nlp/S3D-v1)  

- **S3D-v2**: Contains Tweet IDs for 100,000 tweets labeled automatically by an ensemble of the three best fine-tuned sarcasm detection models.  
  - [Available on HuggingFace](https://huggingface.co/datasets/surrey-nlp/S3D-v2)  

## Experiments

The repository includes a notebook demonstrating the dataset labeling process. The experiments for creating *S3D-v1* and *S3D-v2* can be reproduced using Python notebooks available [here](https://github.com/surrey-nlp/S3D/blob/main/nbs/). The models are loaded via HuggingFace.

## Models Used

| **Model** | **Fine-tuned Version** | **Description** |
|------------|-----------------------|--------------|
| [BERTweet](https://huggingface.co/docs/transformers/model_doc/bertweet) | [bertweet-base-finetuned-SARC-combined-DS](https://huggingface.co/surrey-nlp/bertweet-base-finetuned-SARC-combined-DS) | Fine-tuned on a combined dataset for sarcasm detection |
| [BERTweet](https://huggingface.co/docs/transformers/model_doc/bertweet) | [bertweet-base-finetuned-SARC-DS](https://huggingface.co/surrey-nlp/bertweet-base-finetuned-SARC-DS) | Fine-tuned specifically on the SARC dataset |
| [RoBERTa<sub>large</sub>](https://huggingface.co/roberta-large) | [roberta-large-finetuned-SARC-combined-DS](https://huggingface.co/surrey-nlp/roberta-large-finetuned-SARC-combined-DS) | *RoBERTa-large* model fine-tuned on the combined dataset |

## Maintainers  

- [Jordan Painter](https://github.com/jordanpainter)  
- [Diptesh Kanojia](https://dipteshkanojia.github.io)  
