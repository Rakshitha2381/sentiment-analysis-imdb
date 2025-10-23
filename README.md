# IMDb Movie Review Sentiment Analysis

This project analyzes sentiment (positive/negative) in IMDb movie reviews using Python, Pandas, NLTK, and Scikit-learn.

## Project Overview

The goal was to build a machine learning model capable of classifying movie reviews based on their text content. The final model uses Logistic Regression and achieves approximately 89% accuracy on a dataset of 50,000 reviews.

## Files

* `Sentiment Analysis.ipynb`: Jupyter Notebook containing all the code for data loading, cleaning, preprocessing, model training, evaluation, and visualization.
* `IMDB Dataset.csv`: The dataset containing 50,000 movie reviews and their corresponding sentiments. (Note: This file might be large).

## Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Rakshitha2381/sentiment-analysis-imdb.git](https://github.com/Rakshitha2381/sentiment-analysis-imdb.git)
    cd sentiment-analysis-imdb
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    # source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install pandas numpy nltk scikit-learn matplotlib seaborn jupyterlab
    ```
4.  **Download NLTK data:** Run the first few cells in the Jupyter Notebook to download 'stopwords', 'punkt', and 'punkt_tab'.

## Running the Notebook

1.  Ensure your virtual environment is active.
2.  Start JupyterLab (or Jupyter Notebook):
    ```bash
    jupyter lab
    ```
3.  Open `Sentiment Analysis.ipynb` in the Jupyter interface.
4.  Run the cells sequentially.

## Results

The Logistic Regression model achieved an accuracy of ~89% on the test set. The classification report shows strong performance for both positive and negative classes. Visualizations include sentiment distribution and review word count analysis.
