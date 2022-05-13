# Fine-tuning-XLM-RoBERTa-Multilingual-Sentiment-Analysis

Author: Feifei Wang, Ruixi Zhang

[link to the full paper](finalPaper.pdf)

This project explores the influence of different hyperparameters and fine-tuning methods on XML-RoBERTa’s performance on sentiment analysis tasks for social media texts in five languages: English, Chinese, Urdu, Marathi, and Spanish. Our data are mainly in the form of tweets, with Chinese data, from Weibo, as an exception. We selected hyperparameters like learning rates, number of batches, and epochs and run different trails to find the optimal setting. The one we chose within the time and resource limit is a learning rate of 3e\^5 and a batch size of 64. Further, we explore XLM RoBERTa’s cross-lingual transferability by fine-tuning the model on each language separately and using each model to test the performance in the same task of all five languages. As the result shows that there is relatively uniform performance in every model, our paper validated XLM RoBERTa’s cross-lingual transferability.

![figure1.png](figure1.png)