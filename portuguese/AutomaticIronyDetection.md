# AutomaticIronyDetection
**URL**: [https://github.com/yullidias/AutomaticIronyDetection](https://github.com/yullidias/AutomaticIronyDetection)

**Description**: Automatic irony detection in Portuguese language tweets.

## Research Papers
- **Yulli Dias Tavares Alves, Ana Luiza Sanches, Daniel H. Dalip, and Ismael S. Silva. (2019)**. *Automatic identification of irony: a case study on Twitter*. In Proceedings of the 25th Brazilian Symposium on Multimedia and the Web (WebMedia ’19). Association for Computing Machinery, New York, NY, USA, 253–256. DOI: [10.1145/3323503.3360627](https://doi.org/10.1145/3323503.3360627)
- **Yulli Alves and Daniel Dalip. (2020)**. *Identificação automática de ironia: um caso de estudo no Twitter*. Bachelor’s Thesis, CEFET-MG (Centro Federal de Educação Tecnológica de Minas Gerais), Belo Horizonte, Brazil.

## Dataset Creation
This repository focuses on irony detection in tweets written in Portuguese. Various datasets have been manually annotated and collected for training and evaluation:

### Datasets:
- **#ironia.xlsx** - 61.1 KB
- **#soquenao.xlsx** - 35.1 KB
- **#sqn.xlsx** - 199 KB
- **ironic.xlsx** - 334 KB
- **ironicHashtags.xlsx** - 280 KB
- **manually_ironic.xlsx** - 62 KB
- **manually_not_ironic.xlsx** - 182 KB
- **preprocess.xlsx** - 15.8 MB
- **Ironics.xlsx (train dataset)** - 489 KB

These datasets include manually labeled tweets, some containing hashtags related to irony (#ironia), and others focused on identifying ironic and non-ironic content.

## Training Methods
The repository includes reference code for detecting irony in Portuguese tweets, which was used in the cited research papers. The detection models are built and trained based on the labeled datasets above, although specific training methodologies and models used are not detailed in the repository description.

## Results
While specific evaluation metrics for the models are not provided directly in the repository, the research papers (mentioned above) offer performance metrics based on the experiments conducted. The evaluation of irony detection in Twitter data typically involves comparing the model’s accuracy, precision, recall, and F1 score on the manually annotated datasets. Further results, including detailed metrics, can be found in the related research papers. 
- [Automatic identification of irony: a case study on Twitter](https://doi.org/10.1145/3323503.3360627)