
# Fake News Detection Using Machine Learning and NLP

This repository contains the code, models, and datasets used for a research project focused on detecting fake news across six global news websites. The study applies machine learning techniques such as Neural Networks and Support Vector Machines (SVM), combined with Natural Language Processing (NLP), to improve the reliability and accuracy of fake news identification.

## 🧠 Overview

The main goal of this project is to build and evaluate models that can distinguish between real and fake news articles by analyzing textual content. The research is based on data collected from multiple sources and uses a range of preprocessing and feature extraction methods.

## 📂 Project Structure

```
├── models/                 # Trained machine learning models
├── docs and figures/       # Research paper and all figures related
├── results/                # Evaluation metrics and output reports
├── README.md               # Project documentation
└── requirements.txt        # List of dependencies
```

## 🛠️ Technologies Used

- Python 3.x  
- Scikit-learn  
- TensorFlow / Keras  
- NLTK / SpaCy  
- Pandas / NumPy  
- Matplotlib / Seaborn  

## 🧪 Models Implemented

- Support Vector Machine (SVM)  
- Multilayer Perceptron (MLP)  
- Convolutional Neural Networks (CNN)  
- Long Short-Term Memory Networks (LSTM)  
- Ensemble methods (Voting, Stacking)

## 📊 Evaluation Metrics

- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- ROC-AUC

## 📁 Datasets

Data was gathered from six global news websites and merged with labeled fake/real news datasets available in the public domain. Specific preprocessing was applied to normalize, clean, and tokenize the texts.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection-nlp.git
   cd fake-news-detection-nlp
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run preprocessing and training scripts:
   ```bash
   python src/preprocess.py
   python src/train_model.py
   ```

## 📚 Related Paper

This project is part of a research paper titled:  
**"Thematic Categorization of Fake News in Online News Outlets"**  
*Submitted to the International Journal of Information Management Data Insights (2025).*

## 👤 Author

**Mohammad Torabi**  
Master of Business Administration – Systems & Information Technology  
Data Scientist | NLP Researcher

## 📬 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/moe-torabi-95096271/) or email at mohammad.torabi@outlook.com for collaboration or questions.
