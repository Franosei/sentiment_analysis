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
│   ├── hotel_reviews.csv        # Raw data used for training and testing
├── notebooks
│   ├── sentiment_analysis.ipynb # Jupyter notebook with full implementation
├── environment.yml              # Conda environment file
├── README.md                    # Project documentation

## Installation

To set up the environment for this project, follow these steps:

1. **Create the Conda environment** from the `environment.yml` file:

    ```bash
    conda env create -f environment.yml
    ```

2. **Activate the Conda environment**:

    ```bash
    conda activate sentiment_analysis_env
    ```
This will install all the necessary dependencies listed in the `environment.yml` file and activate the environment for you.

