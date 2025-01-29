# CMGCN
**URL**: [https://github.com/HITSZ-HLT/CMGCN](https://github.com/HITSZ-HLT/CMGCN)

**Description**: [ACL 2022] The source code of Multi-Modal Sarcasm Detection via Cross-Modal Graph Convolutional Network

## Dataset Creation
The dataset used in this repository is a multimodal dataset for sarcasm detection. The data includes both text and images, and it is used to train the CMGCN (Cross-Modal Graph Convolutional Network) model. The dataset is designed to perform sarcasm detection across different modalities, using textual and visual data.

## Training Methods
The training process for sarcasm detection involves the following key steps:
1. **BERT and GloVe Tokenization**: Textual data is tokenized using BERT for deep contextual embedding and GloVe embeddings for word-level representation.
2. **Cross-Modal Graph Construction**: The textual and visual data are integrated into a cross-modal graph, capturing the relationships between different modalities (text and images).
3. **Model Training**: The model is trained using various parameters, such as learning rate, dropout, and L2 regularization, with a multi-task approach for better performance in sarcasm detection tasks.

## Results
The repository reports that the proposed CMGCN model successfully detects sarcasm from multimodal inputs (text and images). However, specific performance metrics (like accuracy or F1-score) are not directly mentioned in the provided description. The model demonstrates the utility of combining textual and visual features to improve sarcasm detection.

### Hyper-parameters and Training Procedure
- The training uses a combination of **BERT-base** and **ViT** (Vision Transformer) models.
- Hyper-parameters include learning rate, batch size, and the use of dropout and L2 regularization to prevent overfitting.
- Models are trained for multiple epochs, and the **early stopping** technique is employed to avoid unnecessary computation.
