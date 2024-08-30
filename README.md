# sentiment_analysis

# Hotel Review Sentiment Analysis

## Overview

This project aims to analyze the sentiment of hotel reviews using machine learning models. The goal is to classify reviews as positive or negative based on the text data provided by customers. Three different models were implemented and compared for their performance:

- **Random Forest**
- **Support Vector Machine (SVM)**
- **Long Short-Term Memory (LSTM) Networks**

The project is structured in a Jupyter Notebook, with the data, models, and results presented in a clear, step-by-step manner.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [How to Run](#how-to-run)
- 
## Project Structure

```plaintext
├── data
│   ├── data.csv                 # Raw data used for training and testing
├── notebooks
│   ├── notebook.ipynb           # Jupyter notebook with full implementation
├── environment.yml              # Conda environment file
├── README.md                    # Project documentation
```

## Installation

To set up the environment for this project, follow these steps:

1. **Create the Conda environment** from the `environment.yml` file:

    ```bash
    conda env create -f environment.yml
    ```

2. **Activate the Conda environment**:

    ```bash
    conda activate sentiment
    ```
This will install all the necessary dependencies listed in the `environment.yml` file and activate the environment for you.

## Data

The dataset consists of customer reviews from various hotels. Each review is labeled as either positive or negative.

-**data.csv: Contains the raw review data with two columns: review (text of the review) and sentiment (label: positive or negative).**

## Models
Three models were implemented and evaluated:

- **Random Forest: A robust ensemble method that operates by constructing multiple decision trees during training.**
- **Support Vector Machine (SVM): A powerful classifier that works by finding the hyperplane that best separates the classes in a high-dimensional space.**
- **LSTM Networks: A type of recurrent neural network (RNN) well-suited for sequence prediction tasks like sentiment analysis.**

## How to Run

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your_username/hotel-review-sentiment-analysis.git
    cd hotel-review-sentiment-analysis
    ```

2. **Activate the environment**:

    ```bash
    conda activate sentiment_analysis_env
    ```

3. **Run the Jupyter Notebook**:

    ```bash
    jupyter notebook notebooks/sentiment_analysis.ipynb
    ```

4. Follow the steps in the notebook to preprocess the data, train the models, and evaluate their performance.


