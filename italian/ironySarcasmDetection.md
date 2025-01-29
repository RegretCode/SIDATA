# ironySarcasmDetection
**URL**: [https://github.com/teelinsan/ironySarcasmDetection](https://github.com/teelinsan/ironySarcasmDetection)

**Description**: This is the code's repository of the paper "A Kernel-based Approach for Irony and Sarcasm Detection in Italian" presented at IronITA @ Evalita2018

## Methods
This repository contains the implementation of the system described in the paper ["A Kernel-based Approach for Irony and Sarcasm Detection in Italian"](http://ceur-ws.org/Vol-2263/paper023.pdf), which was presented at IronITA @ Evalita2018. The system uses a kernel-based approach for detecting irony and sarcasm in Italian text. 

### Key Steps:
1. **Feature Modeling**: The features for sarcasm and irony detection are modeled using a Jupyter notebook (`GenerateKLPFile`), as explained in the paper.
2. **Preprocessing**: Datasets must be preprocessed using a POS-tagger and lemmatizer to generate new dataset copies with preprocessed text.
3. **KeLP**: The system utilizes **KeLP** (Kernel-based Learning Packages) for applying the kernel machine approach to the task.

The approach achieved top ranks at Evalita2018, ranking **first** and **second** at the sarcasm detection task and **sixth** and **seventh** at the irony detection task.

## Results
- **Sarcasm Detection**: Ranked **first** and **second** in the sarcasm detection task.
- **Irony Detection**: Ranked **sixth** and **seventh** in the irony detection task.
- The code implements the feature modeling and classification pipeline, using **KeLP** for kernel-based classification.

## Dataset
- The dataset used for this task is from **IronITA @ Evalita2018**. The dataset can be downloaded [here](http://www.di.unito.it/~tutreeb/ironita-evalita18/data.html).
- The preprocessing requires converting the dataset into `.klp` format using a POS-tagger and lemmatizer, creating processed files like:
  - `test_ironita2018_revnlt_processed.tsv`
  - `training_ironita2018_renlt_processed.tsv`
- The system uses these preprocessed datasets for feature extraction and kernel machine modeling.
