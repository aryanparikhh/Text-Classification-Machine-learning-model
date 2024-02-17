# Text-Classification-Machine-learning-model

The provided Python code focuses on building a text classification model to identify spam messages. Here's a concise summary:

Import Libraries:

Libraries such as Pandas, Scikit-learn for machine learning, NLTK for natural language processing, and WordCloud for visualizations are imported.
Download NLTK Resources:

Necessary NLTK resources (tokenizer and stopwords) are downloaded.
Load and Explore Dataset:

The spam dataset is loaded from the specified path.
Unnecessary columns are dropped, and remaining columns are renamed for clarity.
The dataset is explored to understand its structure and data types.
Text Preprocessing:

Text data is preprocessed by tokenization, stemming, and removal of stop words.
Data Splitting:

The dataset is split into training and testing sets (80% training, 20% testing).
Text Classification with Naive Bayes:

A text classification pipeline is created using CountVectorizer for feature extraction and Multinomial Naive Bayes for classification.
The model is trained on the training set.
Prediction and Evaluation:

The trained model is used to make predictions on the test set.
Accuracy, confusion matrix, and classification report metrics are calculated to evaluate the model's performance.
Word Cloud Visualization:

A Word Cloud is generated for visualizing common words in spam messages.
Visualization Display:

The Word Cloud is displayed for visual exploration.
In summary, this code demonstrates the creation of a text classification model for identifying spam messages. It includes data loading, exploration, text preprocessing, model training, prediction, and evaluation. The Word Cloud visualization offers insights into the most frequent words in spam messages.





