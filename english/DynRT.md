# DynRT
**URL**: [https://github.com/TIAN-viola/DynRT](https://github.com/TIAN-viola/DynRT)

**Description**: Official implementation of **Dynamic Routing Transformer Network for Multimodal Sarcasm Detection (ACL'23)**.

## Overview
This repository contains the **PyTorch code** and **pre-trained models** for the **Dynamic Routing Transformer Network (DynRT)**, as described in the paper *Dynamic Routing Transformer Network for Multimodal Sarcasm Detection*, accepted by ACL 2023.

## Dataset
The model was evaluated using the **Multimodal Sarcasm Detection (MSD)** dataset. To access the required dataset:

1. Download **image data** from [data-of-multimodal-sarcasm-detection](https://github.com/headacheboy/data-of-multimodal-sarcasm-detection) and store it in the folder `dataset_image`.
2. Preprocessed **text data** and labels are available in the folder `input/prepared`. These datasets exclude simple samples (e.g., sarcasm, humor, etc.). 
3. To preprocess the text data, run `clean_dataset.py` to save cleaned data in the `input/prepared_clean` folder.
4. For optimized storage and faster training, the image data is converted into **numpy arrays** and stored in the folder `image_tensor/`.

## Pretrained Model
- Download the **RoBERTa-base** pretrained model and place the files in the `roberta-base/` folder.  
  [RoBERTa-Base Model on HuggingFace](https://huggingface.co/roberta-base)

## How to Use
- To train the model, execute `train.py` with the appropriate parameters configured in the `config/` folder. 
- Training and evaluation results are stored in `exp/{date-time}/`, where `log.txt` contains logs and a JSON file contains the configuration used.

## Model Details
- The training is conducted on **GeForce RTX 2080 Ti GPUs**.
- The **average results** of 5 runs are reported.

## Citation
If you find this repository useful for your research, please cite the following paper:
```bibtex
@article{dynrt2023,
  title={Dynamic Routing Transformer Network for Multimodal Sarcasm Detection},
  author={TIAN-viola et al.},
  journal={ACL 2023},
}
```

## Acknowledgements
- Dataset: Thanks to data-of-multimodal-sarcasm-detection.
- RoBERTa model: Provided by HuggingFace.
- TRAR: Model used from TRAR repository.