# data-of-multimodal-sarcasm-detection
**URL**: [https://github.com/headacheboy/data-of-multimodal-sarcasm-detection](https://github.com/headacheboy/data-of-multimodal-sarcasm-detection)

**Description**: No description provided.

## Project Overview
This repository contains **text and image data** for multimodal sarcasm detection.

## Training Methods:
- **Text Data**:
  - In the **training set**, the last element in each list represents the **label**.
  - In the **validation and testing sets**, two labels are included:
    - The **last but one element** is labeled based on the **original post hashtag**.
    - The **last element** is labeled by a **human annotator**.

- **Preprocessing**:
  - Some posts are **excluded** if they contain specific words such as:
    - *exgag, sarcasm, sarcastic, reposting, joke, humour, humor, jokes, irony, ironic*.
  - The **corresponding images** of these posts are also **not uploaded**.

## Results:
- No explicit model performance metrics or evaluation results are provided in the repository.

## Dataset:
- **Contains both text and image data**, but **some images are missing** due to filtering.
