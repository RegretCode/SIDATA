# MSD
**URL**: [https://github.com/downdric/MSD](https://github.com/downdric/MSD)

**Description**:  
The official implementation of the paper "DIP: Dual Incongruity Perceiving Network for Sarcasm Detection".

## Description
The paper introduces a method for multi-modal sarcasm detection, which focuses on the intrinsic incongruity between image and text pairs in sarcastic data. This method is based on psychological theories that suggest sarcasm involves a contradiction between the literal meaning and the intended meaning, which can be captured through both factual and affective aspects. The proposed method, named **Dual Incongruity Perceiving (DIP) Network**, utilizes two branches: one for the factual aspect of the data and another for the affective aspect.

## Methods
The DIP network is designed with two key components:
1. **Factual Aspect**: This aspect focuses on obtaining semantically discriminative embeddings using a channel-wise reweighting strategy. It also leverages a Gaussian distribution to model the uncertain correlation caused by the incongruity between the image and text. This distribution is generated from the latest data stored in a memory bank, which adaptively models the difference in semantic similarity between sarcastic and non-sarcastic data.
  
2. **Affective Aspect**: This aspect uses **siamese layers with shared parameters** to learn cross-modal sentiment information. A **relation graph** is constructed for the mini-batch using polarity values to form a continuous contrastive loss that helps acquire affective embeddings.

These two branches work in tandem to detect sarcasm by addressing both the factual and emotional contradictions present in sarcastic expressions.

## Results
Extensive experiments show that the **DIP network** outperforms state-of-the-art approaches in multi-modal sarcasm detection, demonstrating its effectiveness in detecting sarcasm by leveraging both the factual and affective cues.

## Dataset
To run the DIP network, you need to download the data from the following source:
- [Multi-Modal Sarcasm Detection in Twitter with Hierarchical Fusion Model](https://github.com/ZLJ2015106/pytorch-multimodal_sarcasm_detection.git)

This dataset consists of multi-modal data (text and images) specifically designed for sarcasm detection.

## Installation
1. **Step 1**: Download the data from the above repository.
2. **Step 2**: Install the necessary packages:
    ```
    torch == 1.13.0
    torchtext == 0.14.0
    torchvision == 0.14.0
    transformers == 4.23.1
    tokenizers == 0.13.1
    senticnet == 1.6
    ```