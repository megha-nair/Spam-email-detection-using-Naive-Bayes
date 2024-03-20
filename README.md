# Spam-email-detection-using-Naive-Bayes
This Python code implements a spam email classifier using the Multinomial Naive Bayes algorithm in scikit-learn. It starts by loading a dataset of spam messages into a pandas DataFrame. After handling missing values and encoding the target variable, the data is split into training and testing sets. Text data is converted into numerical format using CountVectorizer for feature extraction. A Multinomial Naive Bayes classifier is trained on the training set and evaluated for accuracy, precision, and recall on the test set. Additionally, a scikit-learn pipeline is constructed to streamline feature extraction and model training. The pipeline is trained and evaluated on the same dataset. Finally, the trained pipeline is capable of classifying new email messages as spam or non-spam. Key libraries used include pandas for data manipulation and scikit-learn for machine learning tasks. Essential modules utilized from scikit-learn include MultinomialNB for classifier implementation, train_test_split for data splitting, CountVectorizer for text feature extraction, LabelEncoder for encoding categorical labels, and metrics for evaluating model performance. This code snippet serves as a concise example of building a spam email classifier, providing a practical workflow suitable for integration into larger projects.
