# NLP-Classification
News Catogory Classifier
This project builds a machine learning model to classify news articles into categories such as:

Business
Technology
Sports
Education
We use two datasets:

train.csv: for training the model
test.csv: for evaluating the model's performance
The model is trained on the 'headlines' column and predicts the 'category' of each news article.

TF-IDF helps transform text into numeric features suitable for model training

Step 8: Train the Logistic Regression Classifier
We used a simple and effective baseline model: Logistic Regression.

Step 9: Predict on Test Data
The trained model is used to predict categories for the unseen test dataset.

Step 10: Evaluate Model with Classification Report
We use precision, recall,F1-score, and accuracy to evaluate how well the model performs accross all categories.

Step 11: Interactive Classifier
This step allows you to enter your own text(headline) and see the predicted category in real time
