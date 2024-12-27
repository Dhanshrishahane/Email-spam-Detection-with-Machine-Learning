# Email-spam-Detection-with-Machine-Learning

This project focuses on classifying emails as either Spam or Non-Spam, leveraging machine learning and text processing techniques. It includes preprocessing email datasets, feature extraction, model training, and real-time classification functionality.

🔺 Objective
Develop a robust email classification system to identify spam emails and separate them from legitimate ones.

🔹 Technologies Used
Programming Language: Python
Libraries:
Data Processing & Analysis: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: sklearn
Text Processing: TfidfVectorizer for feature extraction.
Machine Learning Algorithm: Logistic Regression.
🔹 Project Steps
Data Preprocessing:

Handle missing values.
Remove irrelevant columns from the dataset.
Encoding Categories:

Label emails as Spam (0) or Non-Spam (1).
Dataset Splitting:

Split the data into training and testing sets.
Feature Extraction:

Use TfidfVectorizer to convert email text into numerical features.
Model Training:

Train a Logistic Regression model on the preprocessed dataset.
Model Evaluation:

Evaluate the model's performance on training and testing data using accuracy metrics.
Visualization:

Bar Plot: Visualize the distribution of emails as Spam and Non-Spam.
Heatmap: Represent the confusion matrix for classification performance.
Real-Time Classification:
Use the trained model to classify new emails in real time.

🔹 Features
Accurate Classification: Differentiates between spam and non-spam emails.
Interactive Visualizations: Gain insights into dataset distribution and model performance.
Real-Time Predictions: Classify unseen emails with the trained model.

🔹 How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/<username>/email-classification-spam.git
cd email-classification-spam
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the script for training and predictions:
bash
Copy code
python main.py

* Future Enhancements
Incorporate advanced NLP techniques like BERT for improved accuracy.
Explore additional machine learning models for better spam detection.
Build
