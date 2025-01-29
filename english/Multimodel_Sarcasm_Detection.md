# Multimodel_Sarcasm_Detection
**URL**: [https://github.com/jesseliu0913/Multimodel_Sarcasm_Detection](https://github.com/jesseliu0913/Multimodel_Sarcasm_Detection)

**Description**:  
This is the undergraduate thesis project for multi-modal sarcasm detection, where I explore how to leverage both text and image data to detect sarcasm. The model combines pre-trained BERT for text and ResNet50 for image data, fused through an attention mechanism and low-rank tensor fusion.

## Methods
The proposed approach uses a combination of pre-trained models and fusion techniques:
1. **Text Feature Extraction**: The text data is processed using the pre-trained BERT model, which is designed to capture contextual word embeddings for sarcasm detection in text.
  
2. **Image Feature Extraction**: The image data is processed using the pre-trained ResNet50 model, which extracts relevant features from images that may help in detecting sarcastic intent.

3. **Fusion Model**: The text and image features are fused using an **attention mechanism** and **low-rank tensor fusion**. This approach ensures that both textual and visual features are integrated effectively, allowing the model to make more informed decisions.

4. **Classification**: The fused features are then passed through a classifier to determine whether the input is sarcastic or not.

## Results
The model is still in the process of optimization. Currently, the results do not meet the expected performance, and further improvements are ongoing. The thesis will continue refining the model to achieve better results, and the author encourages others interested in these methods to reach out.

## Dataset
The dataset used in this work is from the following source:
- **[Multi-Modal Sarcasm Detection in Twitter with Hierarchical Fusion Model](https://aclanthology.org/P19-1239)** (Cai et al., ACL 2019)

This dataset contains multi-modal data (text and images) for sarcasm detection in Twitter posts.
