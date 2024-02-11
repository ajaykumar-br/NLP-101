# Natural Language Processing Notebook

This IPython Notebook explores various Natural Language Processing (NLP) techniques, with a focus on text representation methods and their applications in text classification. The notebook is structured into four main sections, each highlighting different aspects of NLP:

1. **BOW and TF-IDF:**
   - Focuses on text normalization techniques, stemming and lemmatization, using a Wikipedia paragraph.
   - Compares the effectiveness of BOW and TF-IDF methods in text representation.
   - Examines how different n-grams are weighted in each representation technique.
   - Provides a detailed analysis of the impact of text normalization on corpus construction.

2. **Word2Vec:**
   - Utilizes the gensim library for Word2Vec and KeyedVectors, incorporating the 'word2vec-google-news-300' model.
   - Explores Word2Vec functionalities like `most_similar` and `similarity` for semantic analysis.
   - Demonstrates vector arithmetic (e.g., "king - man + woman") to uncover word relationships.
   - Showcases the practical applications and insights gained from pre-trained word embeddings.

3. **Implementing BOW and TFIDF on Spam Dataset:**
   - Applies the Bag of Words model to the SMSSpamCollection dataset, achieving a 97.04% accuracy with MultinomialNB.
   - Implements TFIDF on the same dataset, yielding a 96.05% accuracy with MultinomialNB.
   - Enhances the TFIDF approach with a RandomForestClassifier, achieving a 97.04% accuracy.
   - Highlights the practical effectiveness of BOW and TFIDF in spam classification.

4. **Word2Vec Understanding and Implementation:**
   - Discusses the performance aspects of Word2Vec and introduces the concept of avg-word2vec.
   - Applies avg-word2vec to the spam classification task, providing a deeper understanding of word embeddings.
   - Constructs and evaluates a RandomForest model using avg-word2vec representations.
   - Achieves a remarkable accuracy of 99.64%, showcasing the efficiency of this approach in text classification.

# Dataset Description

The notebook utilizes the 'SMS Spam Collection' dataset for demonstrating text classification techniques. This dataset is a public collection of SMS labeled messages that have been collected for mobile phone spam research. It contains a set of SMS messages in English, tagged as 'spam' or 'ham' (non-spam).

## Key Features of the Dataset:
- **Source:** The dataset is available at the UCI Machine Learning Repository.
- **Contents:** It includes over 5,000 SMS messages, each labeled as either 'spam' or 'ham'.
- **Application:** This dataset is used in the notebook for implementing and comparing different NLP techniques like Bag of Words, TF-IDF, and Word2Vec.

## Dataset Usage in the Notebook:
- The 'SMS Spam Collection' dataset is utilized in both the "Implementing BOW and TFIDF on Spam Dataset" and "Word2Vec Understanding and Implementation" sections, serving as a key resource for practical text classification tasks.
- It provides a real-world application context for exploring various NLP techniques, including BOW, TF-IDF, and Word2Vec, demonstrating their effectiveness in classifying messages as spam or ham.

The dataset can be accessed from the following link: [UCI Machine Learning Repository: SMS Spam Collection Dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection).
