# sentiment-analysis-project
## Overview  
This project demonstrates an end-to-end Sentiment Analysis system that classifies text into **Positive, Negative, or Neutral** sentiments. It leverages Natural Language Processing (NLP) techniques for preprocessing and a Machine Learning model for classification. Additionally, the project includes an interactive **Gradio-based web interface** for real-time sentiment predictions.

## Dataset  
- A custom dataset with **500+ labeled entries** was created for training and evaluation.  
- Each entry contains a text sample and its corresponding sentiment label.  
- Dataset format: CSV file with columns (`text`, `label`).  

## Features  
- Text preprocessing: cleaning, tokenization, stopword removal, TF-IDF vectorization.  
- Machine Learning classification using **Logistic Regression**.  
- Model evaluation with accuracy metrics and confusion matrix.  
- **Gradio web interface** for testing model predictions interactively.  

## Installation  

Clone the repository:  
```bash
git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis
````

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the notebook in Google Colab or Jupyter:

   ```
   Colab_Sentiment_Analysis_End_to_End.ipynb
   ```
2. Upload the dataset file (`custom_sentiment_dataset.csv`).
3. Run all cells to train the model and launch the Gradio app.
4. Enter custom text in the Gradio interface to view predictions.

## Results

* Successfully classified text into Positive, Negative, and Neutral categories.
* Achieved consistent accuracy on the custom dataset.
* Interactive web app provides real-time prediction testing.

## Future Enhancements

* Extend dataset for broader coverage and higher accuracy.
* Experiment with deep learning methods (LSTM, BERT, Transformers).
* Add support for multilingual sentiment analysis. 
