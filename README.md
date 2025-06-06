# 📰 Fake News Detection using Machine Learning

This project focuses on detecting *fake news articles* using Natural Language Processing (NLP) techniques and various *machine learning algorithms. The model is trained to classify news articles as *real or fake based on their textual content.


## 🧠 Key Features

- Cleaned and preprocessed real-world news data.
- Implemented TF-IDF vectorization for feature extraction.
- Trained multiple machine learning models:
  - Logistic Regression
  - Passive Aggressive Classifier
- Evaluated models using accuracy and confusion matrices.
- Achieved high accuracy on test data.

## 🔍 Dataset

The dataset used for training and testing is based on Kaggle’s *Fake News Detection* dataset. It contains two main classes:

- *Real* news  
- *Fake* news

> Columns typically include: title, text, label, etc.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab

### Install Dependencies

Install the required libraries using:

bash
pip install pandas numpy sklearn

bash
git clone https://github.com/CodeNerd25/Fake-News-Detection.git
cd Fake-News-Detection

## 📊 Model Evaluation

The models are evaluated based on:

- *Accuracy Score*  
- *Confusion Matrix*  
- *Precision / Recall*

> Example: Logistic Regression achieved *~96% accuracy* on the test set.

## 🔧 Technologies Used

- *Python* 🐍  
- *Scikit-learn*  
- *Pandas & NumPy*  
- *NLP techniques (TF-IDF)*  
- *Jupyter Notebook*

## ✅ Results

The Passive Aggressive Classifier and Logistic Regression both performed well, with high accuracy in distinguishing between real and fake news articles.

## 📌 Future Improvements

- Improve ANN architecture with deeper layers and better regularization.
- Explore advanced models like LSTM, GRU, or BERT.
- Add more relevant features (e.g., metadata, credibility scores).
- Apply hyperparameter tuning with tools like Optuna or Grid Search.
- Build a web app for real-time predictions (e.g., using Flask or Streamlit).
- Set up model monitoring and periodic retraining for long-term performance.

## 🙌 Contributing

Pull requests are welcome! Feel free to open issues or suggest features.

## 📄 License

This project is open-source and available under the *MIT License*.
