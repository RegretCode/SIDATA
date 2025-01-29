# ToSarcasm
**URL**: [https://github.com/HITSZ-HLT/ToSarcasm](https://github.com/HITSZ-HLT/ToSarcasm)

**Description**: Dataset (ToSarcasm) and Code (TOSPrompt) for CCL 2022 best paper: 面向话题的讽刺识别:新任务、新数据和新方法(Topic-Oriented Sarcasm Detection: New Task, New Dataset and New Method)

## Dataset
- **Name**: ToSarcasm
- **Size**: 2925 training samples, 973 development samples, 973 test samples
- **Language**: Chinese

## Dataset Details
ToSarcasm is a Chinese dataset designed for topic-oriented sarcasm detection. The dataset is divided into three parts: training, development, and testing, with annotations for sarcasm and non-sarcasm.

### Dataset Breakdown:
- **Training**: 2925 samples (1608 sarcastic, 1317 non-sarcastic)
- **Development**: 973 samples (678 sarcastic, 295 non-sarcastic)
- **Test**: 973 samples (623 sarcastic, 350 non-sarcastic)

The dataset is designed to evaluate models in the task of detecting sarcasm based on topics in Chinese text.

We have relabeled the data, and the statistical information of the re-labeled dataset is as follows:

| ToSarcasm     | Train | Dev | Test |
|---------------|-------|-----|------|
| Sarcasm       | 1608  | 678 | 623  |
| Non-Sarcasm   | 1317  | 295 | 350  |
| **All**       | **2925** | **973** | **973** |

For more details on the dataset, please see the [paper](https://aclanthology.org/2022.ccl-1.50/).
