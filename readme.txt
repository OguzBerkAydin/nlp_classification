# NLP Text Classification Project

## Overview
This project implements text classification models to categorize movie plots into different genres. The dataset contains movie plots from 8 different genres: horror, mystery, philosophy, religion, romance, science, science-fiction, and sports.

## Requirements
To run this project locally, install the required libraries:

```
pip install -r requirements.txt
```

## Getting Started
You can run the project in two ways:

### Option 1: Run Locally
After installing the requirements, you can execute the code step by step:

1. Convert the text files to CSV format
2. Preprocess the data
3. Build and train the classification models
4. Evaluate the results

### Option 2: Run in Google Colab
You can also run the entire project in Google Colab by accessing this link:
https://colab.research.google.com/drive/1Z_KvcqyKhXqYGkuyXjxamoYrRgljL6m6?authuser=2#scrollTo=4VOfEXKndEyz

## Project Structure
- `data-nlp/`: Contains the training and testing data
  - `train/`: Training data with movie plots from different genres
  - `test/`: Test data with movie plots from different genres
- `requirements.txt`: List of required Python libraries
- `nlp_homework_oguzberkaydin.ipynb`: Jupyter notebook with the complete code
- `nlp_rapor.pdf`: Detailed report of the project

## Models
The project implements and compares several NLP classification approaches:
- Traditional ML approaches (Naive Bayes, etc.)
- Deep learning approaches (LSTM, etc.)
- Word embeddings and transformers

## Results
The notebook contains detailed visualizations and performance metrics for each model, including:
- Category distribution
- Word clouds
- Confusion matrices
- Accuracy, precision, recall, and F1 scores