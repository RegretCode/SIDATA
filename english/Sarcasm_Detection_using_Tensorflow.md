# Sarcasm_Detection_using_Tensorflow
**URL**: [https://github.com/SanjayKhatwani/Sarcasm_Detection_using_Tensorflow](https://github.com/SanjayKhatwani/Sarcasm_Detection_using_Tensorflow)  

**Description**:  
A deep learning model designed to detect sarcasm in plain text using TensorFlow.

## Dependencies

The project requires the following dependencies:

- Anaconda 4.3.1*
- Python 3.5.x
- TextBlob 0.12.0
- TensorFlow 1.0.1**
- Scikit-learn 0.18.1
- SciPy 0.18.1
- NumPy 1.12.1
- NLTK 3.2.2

## Project Files

The repository contains four main Python scripts:

1. **create_feature_sets.py** – Extracts features from the dataset files and generates `featuresets.npy`.
2. **train_and_test.py** – Uses `featuresets.npy` to train the neural network and saves the trained model inside the `/model/` directory.
3. **exp_replace.py** – Preprocesses the data and is used by `create_feature_sets.py`.
4. **Use_NN.py** – Loads the trained model and allows users to make predictions using the neural network.

## Datasets

The project includes two dataset files:

- `negproc.npy`
- `posproc.npy`

Extracted feature sets are stored in `featuresets.npy`.  
The trained model is stored inside the `/model/` directory.

## Running the Model

1. Run `create_feature_sets.py` to extract features from the datasets.
2. Run `train_and_test.py` to train the model using the extracted features.
3. The trained model will be saved inside `/model/` and can be used for predictions.
4. Use `Use_NN.py` to load the model and make predictions by passing an input sentence to the `use_neural_network()` function.
