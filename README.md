# Sarcasm and Irony Dataset and Analysis

## Table of contents

### English



### Chinese



### French



### Russian



### Spanish



### Persian



### Portuguese



### Korean



### Turkish



### German



### Arabic



This repository aims to gather sarcasm and irony datasets in various languages, comparing how they were created, trained, the results achieved, and how these methodologies can be adapted to Brazilian Portuguese. Our goal is to provide an overview of current approaches and explore how these research findings can be expanded to the Portuguese language, with a focus on the cultural and linguistic adaptation of models.

# Annotated Datasets for Sarcasm and Irony Detection

This repository aims to aggregate and organize datasets for sarcasm and irony detection across different languages, with a primary focus on Brazilian Portuguese. The goal is to provide resources and references for the automatic detection of sarcasm and irony, addressing the linguistic and cultural differences of Brazilian Portuguese.

The repository provides information on how the datasets were created, the training methods applied, the results obtained from different sarcasm and irony detection tasks, and how these methodologies can be adapted for Brazilian Portuguese.

## Project Objective

This final year project aims to understand and automatically identify sarcasm and irony in Brazilian Portuguese. These two rhetorical devices are often ambiguous. Sarcasm expresses the opposite of what is intended, often in a biting manner, while irony is characterized by a discrepancy between the literal and intended meaning. Both are considered complex tasks in Natural Language Processing (NLP).

The primary goal of this project is to create an organized and accessible dataset for sarcasm and irony detection, focusing on Brazilian Portuguese. In addition to organizing existing resources in the literature, the project also aims to establish new collections of sarcasm and irony data in Portuguese. Furthermore, it seeks to evaluate the feasibility of adapting existing techniques from other languages for the Portuguese context.

## How to Contribute

If you'd like to contribute to this repository, you can add new datasets or results by following the guidelines below.

### Guidelines

- **Results**: Results reported in peer-reviewed papers are preferred, though influential preprints may also be accepted.
- **Datasets**: Datasets should have been used for evaluation in at least one published paper besides the paper that introduced the dataset.
- **Code**: If an implementation is available, include a link to it. If not, leave the cell empty.

### Adding a New Result

To add a new result, follow these steps:

1. Click the edit button in the top-right corner of the respective task file.
2. Add a new row to the table, ensuring the results remain sorted with the best result at the top.
3. Preview the changes by clicking on the "Preview changes" tab at the top of the page.
4. Fill out the change proposal form and submit a pull request.

### Adding a New Dataset or Task

To add a new dataset or task, follow these steps:

1. If the task is completely new, create a new file and link it in the table of contents.
2. If not, add the task or dataset to the appropriate section in the file (alphabetically ordered).
3. Briefly describe the dataset/task and include relevant references.
4. Describe the evaluation setup and the evaluation metrics.
5. Provide an annotated example of the dataset/task.
6. Add a download link if available.

Example result table:

| Model           | Score    | Paper / Source  | Code  |
|-----------------|----------|-----------------|-------|
| [Model X]       | 92.3     | Paper Y         | [Link](https://link_to_code.com) |

## Wishlist

These are tasks and datasets that are still missing or needed:

- Sarcasm and irony detection datasets **in Brazilian Portuguese**
- Tools for adapting sarcasm and irony detection models to Brazilian Portuguese
- Datasets and techniques for sarcasm and irony detection in other languages (contributions in any language are welcome!)
- Evaluation of sarcasm and irony detection models in various cultural contexts

## Exporting to a Structured Format

You can extract all the data into a structured, machine-readable JSON format with parsed tasks, descriptions, and SOTA tables. Instructions are available in [structured/README.md](structured/README.md).

## Instructions for Building the Site Locally

If you want to build the site locally using Jekyll, follow the instructions in [jekyll_instructions.md](jekyll_instructions.md).


