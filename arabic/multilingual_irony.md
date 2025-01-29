# multilingual_irony
**URL**: [https://github.com/bilalghanem/multilingual_irony](https://github.com/bilalghanem/multilingual_irony)

**Description**: Irony detection in a multilingual context.

## Dataset
- **Name**: Arabic Irony Corpus
- **Size**:
  - **ECIR dataset**:
    - Training data: 240 KB
    - Testing data: 23.6 KB
  - **IDAT dataset**:
    - Training data: 94.3 KB
    - Testing data: 23.6 KB

## Additional Information

### How the datasets were created
This dataset is part of the research presented in the **Irony Detection in a Multilingual Context (ECIR-2020)** paper.  
- The **Arabic Irony Corpus** consists of approximately **5,500 tweets**, manually annotated by **two native Arabic speakers**.
- An additional **randomly sampled 5,500 tweets** were appended from the original unannotated corpus for the **ECIR dataset** (`ECIR_training.csv` & `ECIR_test.csv`).
- The dataset was also used in the **IDAT shared task at FIRE-2019**, but without the additional random samples to maintain data quality (`IDAT_training.csv` & `IDAT_test.csv`).

Due to **Twitter policy**, only **tweet IDs** are distributed. A Python script (`read_tweets_text.py`) is provided to retrieve the original tweet texts.

### Training methods applied
_Information not available._

### Results obtained
_Information not available._