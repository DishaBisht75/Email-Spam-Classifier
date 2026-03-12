# Email-Spam-Classifier

This project implements an Email Spam Detection System using the Decision Tree machine learning algorithm. The model analyzes email text and classifies messages as Spam or Not Spam (Ham).
The system preprocesses email text, converts it into numerical features using TF-IDF vectorization, and then trains a Decision Tree classifier to detect spam messages.

## OVERVIEW

Spam emails are a major issue in digital communication and can lead to phishing attacks, fraud, and unwanted advertisements. This project builds a machine learning model that automatically filters spam emails based on the content of the message.

The model is trained on a labeled dataset containing spam and legitimate emails.

## FEATURES

1. Text preprocessing (lowercasing, removing numbers and punctuation)
2. Feature extraction using TF-IDF vectorization
3. Spam classification using Decision Tree algorithm
4. Model evaluation using:
   1. Accuracy
   2. Precision
   3. Recall
   4. F1-score
5. Ability to classify new unseen email messages

## TECHNOLOGIES USED

1. Python
2. Pandas
3. NumPy
4. Scikit-learn

## WORKFLOW

1. Load the spam dataset.
2. Clean and preprocess email text.
3. Convert text into numerical features using TF-IDF.
4. Split dataset into training and testing sets.
5. Train a Decision Tree classifier.
6. Evaluate model performance.
7. Use the trained model to classify new emails.

## DATASET

The project uses a labeled spam email dataset containing two classes:

Spam → unwanted or promotional emails

Ham → legitimate emails

## EXAMPLE:

Label	                  Message
Spam	      Congratulations! You won a free prize
Ham	          Meeting scheduled at 3 PM today

## HOW TO RUN

1. Clone the repository

git clone https://github.com/yourusername/email-spam-classifier.git

2. Install required libraries

pip install pandas numpy scikit-learn

3. Run the training script or notebook.

## EXAMPLE OUTPUT
Training Accuracy: 0.95

Message: "Congratulations! You have won a prize"

Prediction: Spam

Message: "Let's meet for lunch tomorrow"

Prediction: Not Spam

## FUTURE IMPROVEMENTS

1. Use Random Forest or Gradient Boosting for better accuracy
2. Apply advanced NLP techniques like word embeddings
3. Build a web interface for real-time spam detection
