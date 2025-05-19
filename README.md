# NLP Text Classification Project

## Overview
This project implements various Natural Language Processing (NLP) techniques to classify movie plots into different genres. The dataset contains movie plots from 8 different genres: horror, mystery, philosophy, religion, romance, science, science-fiction, and sports.

## Dataset
The dataset is organized in the `data-nlp` directory:
- `train/`: Contains text files with movie plots for training (8 genres)
- `test/`: Contains text files with movie plots for testing (8 genres)

Each text file contains movie plots for a specific genre, which are processed and used to train classification models.

## Requirements
To run this project locally, install the required Python libraries:

```bash
pip install -r requirements.txt
```

Required libraries include:
- numpy
- pandas
- matplotlib
- seaborn
- nltk
- wordcloud
- tensorflow
- keras
- scikit-learn
- gensim
- torch
- transformers
- nlpaug

## Getting Started

### Option 1: Run Locally
After installing the requirements, you can execute the code step by step:

1. Clone this repository
2. Install the required dependencies
3. Run the Jupyter notebook `nlp_homework_oguzberkaydin.ipynb`

The notebook includes the following steps:
- Loading and converting text data to CSV format
- Data preprocessing (tokenization, stopword removal, lemmatization)
- Exploratory data analysis and visualization
- Feature extraction (TF-IDF, Word Embeddings)
- Model training and evaluation
- Results visualization

### Option 2: Run in Google Colab
You can also run the entire project in Google Colab by accessing this link:
[Google Colab Notebook](https://colab.research.google.com/drive/1Z_KvcqyKhXqYGkuyXjxamoYrRgljL6m6?authuser=2#scrollTo=4VOfEXKndEyz)

## Project Structure
- `data-nlp/`: Contains the training and testing data
  - `train/`: Training data with movie plots from different genres
  - `test/`: Test data with movie plots from different genres
- `requirements.txt`: List of required Python libraries
- `nlp_homework_oguzberkaydin.ipynb`: Jupyter notebook with the complete code
- `nlp_rapor.pdf`: Detailed report of the project (in Turkish)
- `README.md`: This file

## Models and Techniques
The project implements and compares several NLP classification approaches:
- Traditional ML approaches:
  - Naive Bayes
  - Support Vector Machines
- Deep learning approaches:
  - LSTM (Long Short-Term Memory) networks
  - Bidirectional LSTM
- Word embeddings:
  - Word2Vec
  - GloVe
- Transformers:
  - BERT

## Results
The notebook contains detailed visualizations and performance metrics for each model, including:
- Category distribution
- Word clouds for different genres
- Confusion matrices
- Accuracy, precision, recall, and F1 scores

## License
This project is for educational purposes only.

## Acknowledgments
- Dataset contains movie plots from various genres
- Various NLP techniques and models are implemented for comparison 