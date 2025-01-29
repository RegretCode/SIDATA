# Sarcasm-Detection-ArSarcasm-Dataset
**URL**: [https://github.com/Moamen-Elsayed/Sarcasm-Detection-ArSarcasm-Dataset](https://github.com/Moamen-Elsayed/Sarcasm-Detection-ArSarcasm-Dataset)

**Description**: Sarcasm detection from a collection of Arabic tweets.

## Dataset
- **Name**: ArSarcasm-v2
- **Size**:
  - Training data: 12,548 tweets
  - Testing data: 3,000 tweets
- **Fields**:
  - `tweet`: The original tweet text.
  - `sarcasm`: Boolean indicating whether a tweet is sarcastic or not.
  - `sentiment`: The sentiment of the tweet (positive, negative, neutral).
  - `dialect`: The dialect used in the tweet, categorized into the following:
    - `msa`: Modern Standard Arabic.
    - `egypt`: Dialect of Egypt and Sudan.
    - `levant`: Dialect including Palestine, Jordan, Syria, and Lebanon.
    - `gulf`: Dialect of Gulf countries (Saudi Arabia, UAE, Qatar, Bahrain, Yemen, Oman, Iraq, and Kuwait).
    - `magreb`: Dialect of North African Arab countries (Algeria, Libya, Tunisia, and Morocco).

## Additional Information

### How the datasets were created
ArSarcasm-v2 is an extension of the original **ArSarcasm dataset**, created by combining portions of the **DAICT corpus** and newly annotated tweets. Each tweet was labeled for sarcasm, sentiment, and dialect. The annotations were performed by native speakers, ensuring high-quality data. The dataset was designed to address challenges in sarcasm detection and sentiment analysis and was released as part of a shared task.

### Training methods applied
The dataset utilizes **pre-trained embeddings**:
- **Emoji embeddings**: Pre-trained word-emoji embeddings from **Emoji Embeddings**.
- **Word embeddings**: Pre-trained word embeddings from **Majazak**.

### Results obtained
_Information not available._
