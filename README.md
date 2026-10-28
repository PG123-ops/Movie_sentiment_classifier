# Movie Review Sentiment Analysis using BERT

## Overview

This project uses **Natural Language Processing (NLP)** and **BERT (Bidirectional Encoder Representations from Transformers)** to classify movie reviews based on their sentiment.

A pretrained BERT model is fine-tuned to understand the context of movie reviews and predict whether a review expresses a **positive or negative sentiment**. The project demonstrates how transformer-based deep learning models can be applied to text classification tasks.

## Objectives

- Perform sentiment analysis on textual movie reviews.
- Apply text preprocessing and tokenization techniques.
- Fine-tune a pretrained BERT model for sentiment classification.
- Evaluate model performance using classification metrics.
- Explore the application of transformer-based models to real-world NLP problems.

## Technologies Used

- **Programming Language:** Python
- **Deep Learning / NLP:** BERT, Hugging Face Transformers
- **Libraries:** PyTorch, Pandas, NumPy, Scikit-learn
- **Environment:** Google Colab
- **Version Control:** Git and GitHub

## Project Workflow

The project follows these main steps:

1. **Data Loading:** Load the movie review dataset for analysis and model development.
2. **Text Preprocessing:** Prepare review text for tokenization and model input.
3. **Tokenization:** Convert text into token IDs and attention masks using the BERT tokenizer.
4. **Model Fine-Tuning:** Fine-tune a pretrained BERT model on labeled movie reviews.
5. **Sentiment Classification:** Predict whether each review expresses positive or negative sentiment.
6. **Model Evaluation:** Evaluate the model using accuracy and other relevant classification metrics.

## Model: BERT

BERT is a transformer-based language model that learns contextual representations of words by considering the surrounding text. Unlike traditional approaches that primarily rely on manually engineered features, BERT can capture contextual information that helps distinguish sentiment in natural language.

In this project, a pretrained BERT model is fine-tuned for binary sentiment classification.

## Results

- **Reported Accuracy:** Approximately 89%
- **Task:** Binary sentiment classification
- **Classes:** Positive and Negative

The reported accuracy indicates that the fine-tuned model can classify movie reviews with promising performance on the evaluated dataset.

*Note: Results may vary depending on the dataset split, preprocessing, training configuration, and evaluation setup.*

## Applications

- Movie review sentiment analysis
- Customer feedback analysis
- Opinion mining
- Product review classification
- Text classification using transformer models

## How to Run

The project was developed using Google Colab.

1. Clone or download this repository.
2. Open the project notebook in Google Colab or Jupyter Notebook.
3. Install any required dependencies that are not already available.
4. Load the dataset from the location specified in the notebook.
5. Run the preprocessing, tokenization, model fine-tuning, and evaluation cells.

## Future Improvements

- Evaluate the model using precision, recall, F1-score, and a confusion matrix.
- Experiment with different pretrained transformer models.
- Tune hyperparameters to improve model performance.
- Test the model on unseen movie reviews.
- Develop a simple web application for interactive sentiment prediction.

## Learning Outcomes

Through this project, I explored:

- Transformer-based NLP using BERT.
- Text preprocessing and tokenization.
- Transfer learning and model fine-tuning.
- Sentiment classification and model evaluation.
- The use of Hugging Face Transformers for practical NLP applications.

## Author

**Puspendu Ghosh**

M.Sc. Data Science | Machine Learning | NLP | Generative AI
