# AI-Powered-Privacy-Risk-Classifier-for-Social-Media-Posts

🧩 Problem Statement

In today’s digital world, users constantly share personal information on social media without realizing the privacy risks. Sensitive posts—such as those revealing location, emotions, or personal details—can be exploited for identity theft, phishing, or cyberstalking.

Goal:
Develop an AI-based classifier that detects whether a social media post is “Safe” or “Risky” to share publicly, helping users maintain a secure digital footprint.

🎯 Objectives

Collect or simulate a dataset of social media posts.

Preprocess text data using NLP techniques.

Train a machine learning model to classify posts into Safe or Risky.

Evaluate the model and visualize performance metrics.

Create a simple interface (CLI/Streamlit) to test new posts.

| Component            | Tool/Library Used                                    |
| -------------------- | ---------------------------------------------------- |
| Programming Language | Python 🐍                                            |
| Data Handling        | pandas, numpy                                        |
| NLP Processing       | nltk, scikit-learn                                   |
| ML Algorithm         | Logistic Regression / Random Forest                  |
| Visualization        | matplotlib, seaborn                                  |
| Interface (optional) | Streamlit                                            |
| Dataset              | Custom simulated or Kaggle social media text dataset |

🧠 Possible Improvements

Replace Logistic Regression with BERT / DistilBERT for deeper contextual accuracy.

Expand dataset using Kaggle’s “Social Media Privacy Dataset”.

Deploy on Streamlit or Flask for a web interface.

Add explainability (LIME/SHAP) to show why a post is flagged risky.
