# MUStARD
**URL**: [https://github.com/soujanyaporia/MUStARD](https://github.com/soujanyaporia/MUStARD)

**Description**:  
MUStARD is a multimodal video dataset designed for research in automated sarcasm detection. It contains audiovisual utterances from popular TV shows such as *Friends*, *The Golden Girls*, *The Big Bang Theory*, and *Sarcasmaholics Anonymous*, annotated with sarcasm labels. Each utterance is also accompanied by contextual information from preceding dialogue, allowing for deeper analysis of sarcasm in real-world conversation settings.

## Methods
The dataset includes both video and transcript data:
1. **Raw Video Clips**: The raw video clips, including both the utterances and their respective context, are available for use. This offers the possibility to investigate not only the content of the utterances but also their audiovisual aspects (e.g., facial expressions, tone) that are essential for sarcasm detection.

2. **Contextual Information**: Each utterance is associated with its preceding dialogue, providing context that can be crucial for detecting sarcasm. This contextual setup helps in understanding the sarcasm in the conversation as a whole, rather than just focusing on isolated utterances.

3. **Annotation and Format**: The dataset provides sarcasm annotations in a JSON format, where each instance includes the target utterance, its speaker, the context, the respective context speakers, and a binary label indicating whether the utterance is sarcastic or not.

## Results
As this is a dataset repository, the results are not specified in terms of model performance. The focus of this repository is on providing high-quality data for training and evaluating sarcasm detection models. Researchers can use the dataset to develop models that take advantage of both textual and audiovisual cues in sarcasm detection.

## Dataset
The MUStARD dataset is compiled from several TV shows, and it contains audiovisual utterances annotated for sarcasm. The data format includes:
- **`utterance`**: The text of the target utterance.
- **`speaker`**: The speaker of the utterance.
- **`context`**: A list of preceding utterances in chronological order.
- **`context_speakers`**: A list of speakers corresponding to the context utterances.
- **`sarcasm`**: A binary label indicating if the utterance is sarcastic.

You can access the dataset and raw video clips from the following links:
- [Raw Video Clips](https://huggingface.co/datasets/MichiganNLP/MUStARD/resolve/main/mmsd_raw_data.zip)
- Annotations and Transcripts: [`data/sarcasm_data.json`](data/sarcasm_data.json)

### Example Format:
```json
{
  "1_60": {
    "utterance": "It's just a privilege to watch your mind at work.",
    "speaker": "SHELDON",
    "context": [
      "I never would have identified the fingerprints of string theory in the aftermath of the Big Bang.",
      "My apologies. What's your plan?"
    ],
    "context_speakers": [
      "LEONARD",
      "SHELDON"
    ],
    "sarcasm": true
  }
}
```