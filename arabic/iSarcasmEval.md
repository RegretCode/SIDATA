# iSarcasmEval
**URL**: [https://github.com/iabufarha/iSarcasmEval](https://github.com/iabufarha/iSarcasmEval)

**Description**: Datasets used for iSarcasmEval shared-task (Task 6 at SemEval 2022)

## Methods
The **iSarcasmEval** dataset was created for the iSarcasmEval shared-task, which was part of **SemEval 2022** (Task 6). The dataset includes sarcasm detection data in both **English** and **Arabic**, with each text labeled by its author to reflect its sarcastic nature. Additionally, each sarcastic text is rephrased to convey the same meaning without sarcasm. The dataset also categorizes sarcastic texts into different types of irony, as defined by Leggitt and Gibbs (2000): sarcasm, irony, satire, understatement, overstatement, and rhetorical question.

For the Arabic dataset, there is an additional label specifying the dialect of the text.

## Results
The **iSarcasmEval** shared-task includes three sub-tasks:
- **SubTask A**: Binary classification to determine if a text is sarcastic or non-sarcastic.
- **SubTask B**: Multi-label classification to categorize sarcastic texts into one of the irony types.
- **SubTask C**: Given a sarcastic text and its rephrase, identify which text is sarcastic.

The task's results are evaluated using precision, recall, accuracy, and macro-F1. The main evaluation metrics are:
- **SubTask A**: F1-score for the sarcastic class.
- **SubTask B**: Macro-F1 score.
- **SubTask C**: Accuracy.

## Dataset
The **iSarcasmEval** dataset includes sarcasm detection data in **English** and **Arabic**, with each text containing the following information:
1. **Sarcasm label**: Whether the text is sarcastic or non-sarcastic, provided by the author.
2. **Rephrase**: A rephrased version of the text that conveys the same meaning without sarcasm, provided by the author.
3. **Ironic speech category** (English only): Label for the type of irony, provided by linguistic experts.
4. **Dialect** (Arabic only): The dialect of the Arabic text.

The dataset is part of the SemEval 2022 Task 6: iSarcasmEval. The task covers both sarcasm detection and sarcasm classification for English and Arabic texts.
