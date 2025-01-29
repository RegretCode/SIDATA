# MHSRC
**URL**: [https://github.com/David-deng-01/MHSRC](https://github.com/David-deng-01/MHSRC)

**Description**: Multimodal Humor and Sarcasm Recognition in Chinese: Dataset Construction, Association Analysis and Fine-grained Analysis

## Dataset
- **Name**: MHSRC (Multimodal Humor and Sarcasm Recognition in Chinese)
- **Size**: The dataset details are not specified, but files are provided for download and further processing.

## Download Links
- **BaiduNetDisk**: Links for dataset files including multimodal features and JSON files are provided through Baidu NetDisk (specific download links not listed in the description).

## Dataset Details
The dataset is specifically designed for multimodal humor and sarcasm recognition in Chinese, featuring different types of data processing tasks:

1. **Dataset Splitting**:
   - Download the pre-split dataset [BaiduNetDisk].
   - Alternatively, users can split the data using the script `1_split_data.py`.

2. **Cache Generation**:
   - Cache files are provided for training and validation, which can be downloaded from [BaiduNetDisk].
   - Alternatively, generate cache files by running the script `2_generate_cache.py`, considering oversampling for training and undersampling for validation and test sets.

3. **Class Cache Generation**:
   - For category classification tasks, download processed cache files or generate them using `3_generate_classifier_cache.py`.

4. **Small Model Training**:
   - Users can train small models by running the script `4_train_small_model.py`, after ensuring that cache files are generated in the previous steps.

5. **Multitask Model Training**:
   - Multitask models can be trained with the script `5_train_small_model.py`, utilizing pre-processed data.

6. **Category Classifier Model Training**:
   - To train category classifiers, run `6_train_type_classifier_model.py` after preparing the data.

## Additional Information

- **Objective**: The dataset is used for recognizing humor and sarcasm in Chinese text in a multimodal context. It includes tasks like feature extraction, dataset splitting, and training various models for classification.
  
- **Tasks**: The dataset supports fine-grained analysis of humor and sarcasm, including category classification and multimodal analysis.
