# MMSD2.0
**URL**: [https://github.com/JoeYing1019/MMSD2.0](https://github.com/JoeYing1019/MMSD2.0)

**Description**:  
[ACL2023] Code and dataset for the paper "MMSD2.0: Towards a Reliable Multi-modal Sarcasm Detection System".

## Description
Multi-modal sarcasm detection has garnered significant attention in recent years. However, the existing benchmark (MMSD) has several shortcomings that hinder the development of reliable multi-modal sarcasm detection systems. The issues include spurious cues that lead to model bias and unreasonable negative samples. To address these challenges, MMSD2.0 introduces a corrected dataset by removing spurious cues and re-annotating the unreasonable samples. Additionally, a new framework called **multi-view CLIP** is presented, which utilizes multi-grained cues from multiple perspectives (text, image, and text-image interaction) for multi-modal sarcasm detection. Extensive experiments show that MMSD2.0 is a valuable benchmark for developing reliable multi-modal sarcasm detection systems, and the multi-view CLIP framework outperforms previous baselines by a 5.6% improvement.

## Methods
The MMSD2.0 framework utilizes **multi-view CLIP**, which combines several perspectives:
1. **Text View**: Extracting textual features to understand the sarcastic meaning.
2. **Image View**: Incorporating image features to capture visual cues related to sarcasm.
3. **Text-Image Interaction View**: Leveraging the interaction between text and images for a more comprehensive understanding of sarcasm.

These views help overcome the shortcomings of previous systems, especially by mitigating biases and improving the quality of negative samples.

## Results
Extensive experiments demonstrate that MMSD2.0 provides a reliable benchmark for multi-modal sarcasm detection. The multi-view CLIP method significantly outperforms previous state-of-the-art baselines, showing a 5.6% improvement in detection accuracy.

## Dataset
- **MMSD (Original dataset)**: The original MMSD dataset can be found in the folder `data/text_json_clean`.
- **MMSD2.0 (Corrected dataset)**: The updated and corrected dataset, which addresses the shortcomings of the original, is located in `data/text_json_final`.

These datasets include texts with images and textual annotations that can be used for training and testing multi-modal sarcasm detection models.
