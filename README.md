# Text Classification Project: AI vs Human Text Detection

This project is a machine learning pipeline designed to classify text as AI-generated or human-generated. The project utilizes a Kaggle dataset and includes data preprocessing, model training, and evaluation steps.

## Project Structure

- **Data Setup**: Downloads and unzips the dataset from Kaggle.
- **Preprocessing**: Cleans and processes the dataset for text classification.
- **Modeling**: Builds, trains, and evaluates a machine learning model on the processed data.

## Requirements

- Python 3.7+
- Jupyter Notebook
- Kaggle API for dataset download

## Installation

1. **Install Kaggle API**:
   ```bash
   !pip install kaggle
## Download dataset from kaggle
!kaggle datasets download -d shanegerami/ai-vs-human-text
## Unzip it
!unzip ai-vs-human-text.zip
