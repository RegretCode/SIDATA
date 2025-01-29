# Sentiment-Analysis---Amazon-Fine-Food-Reviews  
**URL**: [https://github.com/amritajose/Sentiment-Analysis---Amazon-Fine-Food-Reviews](https://github.com/amritajose/Sentiment-Analysis---Amazon-Fine-Food-Reviews)  

## Description  
This project focuses on implementing a sentiment analysis system using NLP techniques to interpret language complexities such as context, ambiguity, sarcasm, and irony in user reviews. The dataset used is the fine food reviews from Amazon, aiming to assist customers in making faster and more informed decisions regarding the products. The system also includes a review summarization feature to condense reviews to less than 20 words.

### Project Overview  
- **Sentiment Analysis**: The system uses three machine learning models—Logistic Regression, Naïve Bayes, and K Nearest Neighbor—to predict and classify the sentiment of reviews as positive or negative.
- **Summarization**: The system also includes two summarization techniques to provide brief summaries for customers who prefer quick reads. The reviews are summarized using NLTK and N-grams, and sentiment is captured from both the original reviews and their summaries.

### Solution Implementation  
1. **Data Preprocessing**: Handling missing values, duplicates, redundant data, and adding new variables for analysis.
2. **Random Under Sampling**: To ensure even class distribution for better model performance.
3. **Sentiment Classification**: Using three models—Logistic Regression, Naïve Bayes, and K Nearest Neighbor—and vectorizing the data with Bag of Words and TF-IDF.
4. **Exploratory Analysis**: Analyzing data distribution, generating word clouds, and identifying helpful reviews.
5. **Sentiment Prediction**: Evaluating the sentiment of reviews using the implemented machine learning models.
6. **Summarization**: Reviews are summarized to less than 20 words using NLTK, with the sentiment of these summaries compared to the original reviews.
7. **Model Evaluation**: Comparing the performance of the models and summarization techniques based on accuracy.

### Dataset  
The dataset used in this project is the Amazon Fine Food Reviews dataset, which contains product reviews and ratings. It is available for download on Kaggle at:  
[Amazon Fine Food Reviews Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews).

## Results  
- **Sentiment Classification**: The models predict sentiment accurately, classifying reviews as positive or negative.
- **Summarization**: The summarization techniques provide concise reviews with captured sentiment, enhancing the decision-making process for customers.
  
## Sample Input and Output  
- **Input**:  
  *User Review 1*: "This is one food that when mixed with their dry food, my dogs will eat every last drop. They love this. Our older dog (just turned 2) needs to be on a grain free diet, so that is what our puppy gets too. I love that this is 95% Turkey and that the dogs really like it."  
  *Output*: Predicted Sentiment: 1 (Positive)

- **Input**:  
  *User Review 2*: "My son is on a restricted diet due to allergies and he is very picky. It was hard to find things that he would even try. After tasting one of these cookies he was hooked. Now this is a favorite snack of his."  
  *Output*: Predicted Sentiment: 1 (Positive)

- **Input**:  
  *User Review 3*: "This is so frustrating. Where is the nutritional information? They tell you what's not in it, but they don't tell you what is in it. Furthermore, I had to enlarge the image to get that information. What are they trying to hide? Due to their less-than-generous return policy, I would never buy a product from Amazon.com unless I know exactly what I am getting. Ya got that Amazon?!"  
  *Output*: Predicted Sentiment: 0 (Negative)

- **Input**:  
  *User Review 4*: "Followed the directions to a the letter and ended up with a ridiculously sticky mess that had to be thrown out."  
  *Output*: Predicted Sentiment: 0 (Negative)