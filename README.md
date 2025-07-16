# Movie Review Sentiment Analysis Using LSTM and NLP

A deep learning project that classifies movie reviews as **positive** or **negative** using **NLP preprocessing** and a **Long Short-Term Memory (LSTM)** model. Trained on the IMDb dataset, this project explores sentiment analysis using sequential models.

---

## Project Overview

The project uses movie review data to build a **binary classifier** that determines whether a review is positive or negative. It uses **LSTM**, a type of recurrent neural network (RNN) capable of learning long-term dependencies, making it ideal for sequence-based text data.

---

## Tech Stack

- **Python**
- **TensorFlow / Keras** – Deep learning model (LSTM)
- **Pandas, NumPy** – Data manipulation
- **NLTK / Regex** – Text preprocessing
- **Matplotlib / Seaborn** – Visualization

---

## Features

-  Load and preprocess IMDb review data  
-  Clean and tokenize text using NLTK  
-  Convert text to padded sequences  
-  Train LSTM-based sentiment classifier  
-  Visualize accuracy and loss over epochs  
-  Evaluate model on test data

---

## File Structure

```
Movie-Review-Sentiment-Analysis-Using-LSTM-and-NLP/
│
├── movie_sentiment_lstm.ipynb      # Jupyter notebook with code
├── IMDb Dataset (optional)         # Load via TensorFlow datasets or CSV
├── README.md                       # Project documentation
```

---

## Dataset

- **Source**: IMDb movie reviews dataset  
- **Classes**: `positive`, `negative`  
- **Split**: 80% training, 20% testing  
- **Total Reviews**: 50,000

---

## How It Works

1. **Text Preprocessing**
   - Lowercasing, punctuation removal, stopword filtering  
   - Tokenization and sequence padding  

2. **Model Architecture**
   - Embedding Layer  
   - LSTM Layer  
   - Dense output layer with sigmoid activation  

3. **Training**
   - Binary crossentropy loss  
   - Adam optimizer  
   - Accuracy as evaluation metric  

---

## Results

- **Accuracy**: ~88–90% on test set  
- **Model**: LSTM  
- **Loss Function**: Binary Crossentropy  
- **Epochs**: 10–15  
- **Evaluation**: Confusion matrix and accuracy/loss plots

---


## Future Improvements

- Try GRU, BiLSTM, or transformer-based models like BERT  
- Implement attention mechanism  
- Convert into a Streamlit or Flask app  
- Add a review input box for real-time sentiment prediction

---



