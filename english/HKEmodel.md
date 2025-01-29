# HKEmodel
**URL**: [https://github.com/less-and-less-bugs/HKEmodel](https://github.com/less-and-less-bugs/HKEmodel)

**Description**: Official implementation of Towards Multi-Modal Sarcasm Detection via Hierarchical Congruity Modeling with Knowledge Enhancement.

## Methods
This repository provides the official implementation of the paper *Towards Multi-Modal Sarcasm Detection via Hierarchical Congruity Modeling with Knowledge Enhancement* (2022). The model uses hierarchical congruity modeling combined with knowledge enhancement to improve sarcasm detection across multiple modalities.

Key steps and components of the method:
- **Text-Image Branch**: The model includes a text-image branch for multimodal inputs. The final classification layer differs depending on the knowledge enhancement: one-layer MLP is used without knowledge enhancement, and two-layer MLP is used with knowledge enhancement.
- **Knowledge Enhancement**: A knowledge enhancement technique is used to improve performance, and the model includes two versions: one with and one without knowledge enhancement.
- **Hyperparameters**: The model's hyperparameters are defined in a `parameter.json` file, which must be configured for training.

For further implementation details, you may refer to the provided `train.py` and `data_process.ipynb`.

## Results
The experiments were run on a 24-GB 3090Ti GPU, with approximately one hour for each run. The authors report average results from multiple runs, providing stable performance across evaluations. The total number of parameters in the model is **112,540,942**.

You can refer to the provided code to evaluate the performance and reproduction of the results, though exact performance metrics are not listed in the description.

## Dataset
The dataset used for training and testing the model is available for download via the link provided:
- **Dataset Link**: [Download here](https://portland-my.sharepoint.com/:u:/g/personal/liuhui3-c_my_cityu_edu_hk/Eb59O8EpvO5Ft_M4FKmfPgsBjq_V_1HefEyooyjpL2t8yA?e=lTw6Up)
- For the original dataset, please refer to [data-of-multimodal-sarcasm-detection](https://github.com/headacheboy/data-of-multimodal-sarcasm-detection).

Make sure to unzip the dataset and place it in the project directory before running the code.
