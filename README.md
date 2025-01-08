# Multi-class text classification using machine learning to detect customer service calls intent

- Project aimed at labeling customer service calls using conversation transcripts. Large language models were used to generate initial labels, resulting in 57 unique labels.

- Since relying solely on LLMs was not feasible, simpler and more efficient models, such as TF-IDF and distilBERT, were trained for multi-label classification to enable routine or real-time text classification. Call transcript data was cleaned and standardized for model training.

- distilBERT, a lightweight version of BERT, outperformed TF-IDF in accurately predicting call labels, achieving an F1-score of 74% on validation data.

- Sentiment scores were generated for each call, and predicted labels were analyzed to identify those associated with higher percentages of negative sentiment and unusually long durations. Recommendations included automating responses for common issues and providing employee training for calls with longer durations or negative sentiment, with the goal of improving efficiency and customer satisfaction.
