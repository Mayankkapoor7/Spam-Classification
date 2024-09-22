# Spam-Classification
This repository contains a Spam Classification Model built using the Random Forest Classifier. The model is designed to classify messages (such as emails or SMS) as either spam or not spam based on their content. It leverages machine learning techniques to automatically detect spam messages with high accuracy.
Key Features:
Text Preprocessing with Bag of Words (BoW):

The model uses Bag of Words (BoW) to convert text data into a numerical format. BoW represents each message as a vector of word counts, where the presence (or absence) of each word is captured without considering the order.
This helps the model focus on word frequency and patterns in spam messages, which improves classification performance.
Random Forest Classifier:

Utilizes the power of ensemble learning to create a robust and effective model. Random Forest builds multiple decision trees and combines them to improve classification accuracy and handle high-dimensional text data efficiently.
Pipeline Implementation:

A streamlined machine learning pipeline is used to handle both the text transformation (via BoW) and model training (via Random Forest) efficiently in one flow.
