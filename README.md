# simple-content-classifier
Dataset creation: We'll manually define a small dataset with webtoon descriptions and their corresponding categories.

Text preprocessing: We'll clean and vectorize the descriptions using TfidfVectorizer.

Model selection: We can use either Logistic Regression or a Decision Tree classifier from scikit-learn.

Training and evaluation: Train the model on the dataset and evaluate the output.

# Explanation
Dataset: A dictionary contains 15 webtoon descriptions with their corresponding categories such as "romance," "action," and "fantasy."

Vectorization: We use TfidfVectorizer to convert text data into numerical features. This is important because machine learning models can't handle raw text.

Modeling: Both a Decision Tree and Logistic Regression classifier are trained on the webtoon descriptions.

Evaluation: We use accuracy and classification reports (precision, recall, f1-score) to evaluate the models' performance on unseen data (30% test set).
