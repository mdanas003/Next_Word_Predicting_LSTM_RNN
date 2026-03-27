# Next Word Prediction using LSTM

### NLP Sequence Modeling + Deep Learning Application

A deep learning project that predicts the **next word in a sequence of text** using Long Short-Term Memory (LSTM) networks.

This project demonstrates how sequential text data can be modeled using neural networks to understand language patterns and generate meaningful predictions.

---

## Features

### Text Processing
* Tokenization  
* Sequence Generation  
* Text to Numerical Encoding  

### Deep Learning Model
* LSTM (Long Short-Term Memory)  
* Sequential Neural Network  
* Trained on text dataset  

### Application
* Interactive Streamlit web app  
* User input based prediction  
* Real-time next word generation  

---

## Tech Stack
* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Streamlit**

---

## System Architecture


Raw Text Dataset

↓

Text Preprocessing

↓

Tokenization

↓

Sequence Creation

↓

LSTM Model Training

↓

Prediction

↓

Next Word Output

---

## Project Workflow

1. Load text dataset  
2. Perform preprocessing and tokenization  
3. Generate input sequences  
4. Train LSTM model  
5. Save trained model and tokenizer  
6. Build Streamlit app for interaction  
7. Predict next word based on user input  

---

## Repository Structure


Next-Word-Prediction-LSTM/

│

├── app.py

├── Practical.ipynb

├── next_word_lstm.h5

├── tokenizer.pickle

├── hamlet.txt

├── requirements.txt


---

## Key Concepts Covered
* Sequence modeling  
* Text generation  
* LSTM architecture  
* Tokenization and encoding  
* Deep learning for NLP  

---

## Installation

git clone https://github.com/YOUR_USERNAME/Next-Word-Prediction-LSTM.git  
cd Next-Word-Prediction-LSTM  

---

## Usage

streamlit run app.py  

---

## Example

Input: "To be or not to"  
Output: Predicted next word  

---

## Future Improvements

* Larger training datasets  
* Advanced models (GRU, Transformers)  
* Beam search for better predictions  
* Deployment on web platforms  

---

## Author

Mohammed Anas  
B.Tech IT Student | AI & ML Enthusiast
