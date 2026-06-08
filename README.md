# Disaster-Tweet-Classification-Project-
This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets as disaster-related or non-disaster-related. Built and trained in Google Colab, the model leverages text preprocessing, tokenization, and feature extraction techniques to improve classification accuracy.

📌 Motivation

The Kaggle "Disaster Tweets" dataset provided the initial foundation. However, during exploration it became clear that the dataset was poorly labeled, with many tweets incorrectly tagged as disasters or non-disasters.
To address this, a custom dataset was curated and cleaned, resulting in significantly better model performance and more reliable predictions.

🚀 Features
- Text preprocessing: tokenization, stopword removal, stemming, and normalization

- Model training with Logistic Regression, Naive Bayes, and Random Forest

- Performance evaluation using Confusion Matrix, ROC–AUC Curve, and F1-score

- Threshold tuning guided by ROC–AUC analysis

- Visualizations for interpretability and model comparison

📈 Results

On the Kaggle dataset: performance was limited due to noisy labels.

On the custom dataset: the model achieved substantially higher accuracy and AUC scores, demonstrating the importance of high-quality data.

📈 Model Performance

Dataset	          	  	
* Kaggle (original)  	Accuracy ~ 0.72	  F1-Score ~ 0.70	     ROC–AUC ~ 0.74
* Custom (curated)	  Accuracy ~ 0.89	  F1-Score ~ 0.88	     ROC–AUC ~ 0.91

- Observation: The Kaggle dataset’s noisy labels limited performance.

- Improvement: On the custom dataset, the models achieved substantially higher accuracy and AUC scores, proving the importance of high-quality data.

🧩 Tech Stack

- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)

- Google Colab

- Dataset: Kaggle Disaster Tweets + Custom curated dataset
