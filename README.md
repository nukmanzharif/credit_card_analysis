# Credit Card Transaction Analysis

## Overview
This project analyzes credit card transactions using PySpark, providing insights into transaction patterns and fraud detection. It processes a large JSON dataset, performs data cleaning, and generates visualizations.

## Installation

### 1. Clone the Repository
- `git clone <repository-url>`

### 2. Download the Dataset
- Download the dataset from [here](https://www.kaggle.com/datasets/e47f88e5e8ce59c9598475a107d9a80ebc363a83859a59facb069b13a9001773)
- Extract the content and place it in the same directory as the `credit_card_analysis.ipynb` file

### 3. Create Virtual Environment
- `python -m venv venv`
- `.\venv\Scripts\activate.bat` (Windows)

### 4. Install Dependencies
- `pip install -r requirements.txt`


### 5. Install Java (if not installed)
- Download and install Java from [Oracle's website](https://www.oracle.com/java/technologies/downloads/)
- Set JAVA_HOME environment variable

## Usage
1. Start the Jupyter Notebook
2. Open the `/Credit Card Transaction Analysis.ipynb` file
3. Run all cells in sequence

## Output Files
- `cleaned_transactions_final.csv`: Cleaned and transformed dataset
- `cleaned_transactions_sample.csv`: Sample dataset (if full export fails)

` pip freeze > requirements.txt`