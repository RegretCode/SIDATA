# Sarcasm Target Detection  
**URL**: [https://github.com/Pranav-Goel/Sarcasm-Target-Detection](https://github.com/Pranav-Goel/Sarcasm-Target-Detection)  

## Description  
This project introduces a **manually labeled dataset** for the **novel task of Sarcasm Target Identification**. It focuses on detecting **the specific subset of words in a sarcastic text** that indicate the **entity or situation being ridiculed**.  

## Dataset  
The dataset consists of two manually annotated files:  
- **snippets.xlsx**: Contains **224 book snippets** labeled for sarcasm targets.  
- **tweets.xlsx**: Contains **506 sarcastic tweets**, each annotated to identify sarcasm targets.  

### Annotation Scheme  
- The **sarcasm target** is a subset of words in the text that refer to the **entity or situation** being ridiculed.  
- If no target is explicitly present within the text, a fallback label of **"Outside"** is assigned.  

## Citations  
If using the **snippets dataset**, please cite:  
- Joshi, Aditya, Pranav Goel, Pushpak Bhattacharyya, and Mark Carman.  
  - *Sarcasm target identification: Dataset and an introductory approach.*  
  - **LREC 2018 - Eleventh International Conference on Language Resources and Evaluation**.  

If using the **tweets dataset**, please refer to the extended version available at:  
- **ALTA 2019 Shared Task**: [http://www.alta.asn.au/events/sharedtask2019/description.html](http://www.alta.asn.au/events/sharedtask2019/description.html)  
- Citation:  
  - Molla, Diego, & Joshi, Aditya (2019).  
  - *Overview of the ALTA 2019 shared task: sarcasm target identification.*  
  - In *Proceedings of the 17th Annual Workshop of the Australasian Language Technology Association*.  

## Implementation & Results  
⚠ **Lack of Information**:  
- No details on **methods, models, or evaluation metrics** are provided.  
- There is **no implementation code** for sarcasm target detection beyond the dataset itself.  