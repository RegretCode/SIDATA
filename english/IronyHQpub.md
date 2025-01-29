# IronyHQpub
**URL**: [https://github.com/joernklinger/IronyHQpub](https://github.com/joernklinger/IronyHQpub)

**Description**: Tools for Sarcasm Detection in Tweets

## Methods
IronyHQ is a set of tools designed for sarcasm detection in Tweets. It consists of three main components:
- **Stream**: Allows streaming of Tweets based on keywords or location.
- **Annotation**: Loads Tweets and provides a web interface for annotation. This interface is set up to work with **Amazon Mechanical Turk**.
- **Processing**: Analyzes collected Tweets, finding accounts that the author of each Tweet follows, and adds this data to the Tweet's metadata.

The system also involves the following steps for installation and setup:
1. Clone the repository.
2. Set up **MongoDB** with a database named `IronyHQ` and a collection named `tweets`.
3. Install necessary Python modules.
4. Set up and configure the **Annotation** server.
5. Stream Tweets and process them based on your Twitter API credentials.

## Results
- This repository provides a toolset for sarcasm detection and Tweet processing, but there is no direct mention of performance metrics, such as accuracy or F1 score, in the repository.
- The main focus is on setting up the tools for data collection and annotation, and not on predefined model performance.

## Dataset
- The dataset is collected from **Twitter** through streaming Tweets based on specific keywords or locations.
- Tweets are stored in the `IronyHQ` MongoDB database.
- No specific dataset is provided within the repository; the tools are intended for users to collect their own data for sarcasm detection.

