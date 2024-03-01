# Movie-Reviews-Sentiment-Analysis
The main goal of my project was to perform sentiment analysis on the IMDb dataset to classify movie reviews as positive or negative.
## 1. Initial Setup and Data Exploration:
Utilized Python libraries such as pandas for data manipulation, matplotlib and seaborn for visualization, and nltk for natural language processing tasks.
Conducted an initial exploration of the dataset to assess class balance and understand the distribution of sentiments.
## 2. Data Preprocessing:
Implemented text cleaning techniques to remove HTML tags and URLs from the reviews using BeautifulSoup and regular expressions.
Analyzed the word count distribution for both positive and negative reviews, providing insights into the dataset's composition.
Applied further text preprocessing steps including the removal of punctuations, tokenization, and the elimination of stopwords to refine the reviews for analysis.
Explored both stemming and lemmatization to normalize the text, reducing words to their base or root form, and prepared the processed text for vectorization.
## 3. Feature Engineering:
Converted the cleaned and normalized reviews into a matrix of TF-IDF features, preparing the data for machine learning modeling.
## 4. Modeling with Multinomial Naive Bayes:
Chose the Multinomial Naive Bayes classifier due to its suitability for text classification tasks. Trained the model on the preprocessed and vectorized text data.
Evaluated the model using classification reports and confusion matrices, assessing its performance in accurately predicting sentiments.
## 5. Addressing Class Imbalance:
Investigated the impact of class imbalance on model performance by creating datasets with varying ratios of positive to negative reviews.
Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes in the dataset, observing improvements in model accuracy and fairness.
## 6. Model Evaluation and Iteration:
Conducted a thorough evaluation of the model across different levels of class imbalance, utilizing confusion matrix displays to visually interpret the model's performance.
Refined the modeling approach by retraining the Multinomial Naive Bayes classifier on balanced datasets, achieving significant enhancements in classification metrics.
