# Text-Emotions-Classification

## Description

The Text-Emotions-Classification project is a machine learning application focused on classifying textual data into predefined emotional categories using Natural Language Processing (NLP) techniques. The project implements various NLP methods alongside machine learning algorithms to effectively process and analyze text data, achieving accurate classification results.

## Objectives

- Develop a robust text classification model that accurately categorizes text documents.
- Utilize advanced NLP techniques for effective text preprocessing, such as tokenization, stemming, lemmatization, and vectorization.
- Evaluate and compare the performance of different classification algorithms (e.g., Logistic Regression, Support Vector Machines, and Neural Networks).
- Create an intuitive interface for users to input text and receive classification predictions.

## Features

- **Text Preprocessing:**
  - Tokenization
  - Removing stop words and punctuation
  - Stemming and lemmatization
  - TF-IDF vectorization

- **Model Training:**
  - Train deep learning and machine learning models
  - Track Training Accuracy, Validation Accuracy, Training Loss, and Validation Loss

- **Visualization:**
  - Generate plots to visualize the metrics over epochs for better understanding of model performance

- **User Interface:**
  - A simple command-line or web interface for users to input text and receive classification results

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - `scikit-learn` for machine learning algorithms
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `nltk` or `spaCy` for NLP processing
  - `matplotlib` and `seaborn` for data visualization

## Model Evaluation

The model's performance can be evaluated using metrics such as accuracy, precision, recall, and F1-score. After training the model, you can use the `evaluate` method to get insights on its performance:

loss, accuracy = model.evaluate(x_test, y_test)

print("Accuracy of the model:", accuracy)

print("Model loss:", loss)

## Installation & Usage

### Installation
1. Clone this repository:
   ```bash
    git clone https://github.com/HemanshiTimbadiya/Text-Emotions-Classification.git
2. Navigate to the project directory:
   ```bash
   cd Text-Emotions-Classification
   
4. Install the required packages:
   ```bash
   pip install -r requirements.txt

### Usage
- Run the analysis in a Jupyter Notebook.
- To deploy the project using Streamlit, run:
  ```bash
  streamlit run text_app.py 

