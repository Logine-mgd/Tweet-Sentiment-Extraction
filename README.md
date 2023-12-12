# Welcome to the Tweet Sentiment Extraction project! 

In today's fast-paced world, tweets have become a powerful tool for expressing opinions and influencing public perception. With thousands of tweets being posted every second, it's challenging to determine whether a particular tweet will positively or negatively impact a brand's reputation. Sentiment analysis can help businesses and individuals identify and address potential issues before they escalate. However, identifying the words that contribute to the overall sentiment of a tweet remains a crucial task.

## Dataset
To tackle this problem, we utilized the dataset from the Kaggle competition [Tweet Sentiment Extraction](https://www.kaggle.com/c/tweet-sentiment-extraction) and Figure Eight's Data for Everyone platform 🌎. This dataset contains a collection of tweets along with their corresponding sentiment labels (positive, negative, or neutral). By analyzing these labeled tweets, we aim to develop a model that can show which words lead to particular sentiment.


## Implementation

This project presents an implementation for the extraction of words influencing sentiment, employing two distinct models: DistilBERT and TinyRoBERTa. The DistilBERT model, fine-tuned with pre-trained models from Hugging Face, achieved an impressive Jaccard score of 68.11. DistilBertForQuestionAnswering, a model built on top of the DistilBERT architecture, was specifically tailored for question answering tasks, has been used for words extraction. PyTorch Lightning was employed for its flexibility, enabling the creation of custom datasets, modules, and models to optimize performance. Additionally, the TinyRoBERTa model, yielding a Jaccard score of 65.85, highlights the versatility of this implementation. The combination of fine-tuning, architecture customization, and the utilization of pre-trained models resulted in competitive performance, making this implementation a powerful tool for accurate extraction.
