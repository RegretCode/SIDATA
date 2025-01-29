# Irony-Sarcasm-Detection-Task
**URL**: [https://github.com/lorenzofamiglini/Irony-Sarcasm-Detection-Task](https://github.com/lorenzofamiglini/Irony-Sarcasm-Detection-Task)

**Description**: The detection of irony and sarcasm is one of the most insidious challenges in the field of Natural Language Processing. Over the years, several techniques have been studied to analyze these rhetorical figures, trying to identify the elements that discriminate, in a significant way, what is sarcastic or ironic from what is not. 

## Methods
- **Machine Learning Models**: The study analyzes state-of-the-art models in irony and sarcasm detection.
  - Key features analyzed include part of speech, pragmatic particles, and sentiment.
  - Models are optimized using Bayesian optimization and random search.
  - Ensemble methods such as Bayesian Model Averaging (BMA) are employed after identifying the best hyperparameters.

- **Deep Learning Models**:
  - Two primary models are used: DeepMoji (developed by MIT) and a Transformer-based model using the power of the Roberta Transformer.
  - Attention mechanisms and Transfer Learning are used in new proposed models.
  - Bert Tweet Model and DeepMoji Model are used as feature extractors.
  
- **Ensemble Methods**: The final system combines the best algorithms using ensemble techniques for improved results.

- **Frameworks**: 
  - Pytorch
  - TensorFlow 2.0
  - Scikit Learn
  - Scikit-Optimize
  - Transformers
  
## Results
- **Goal**: To identify a system that better captures both sarcasm and irony in text.
- The models are evaluated based on their ability to generalize over out-domain datasets and their capacity to detect patterns of irony and sarcasm with satisfactory performance.

## Dataset
- **Data Source**: 
  - The dataset was collected using various ids provided by the authors of different papers.
  - Due to Twitter restrictions, training and test data cannot be shared.
  
- **Data Access**: No dataset is directly available in this repository due to privacy and licensing constraints. Data can only be accessed by contacting the authors or through the provided paper references.
