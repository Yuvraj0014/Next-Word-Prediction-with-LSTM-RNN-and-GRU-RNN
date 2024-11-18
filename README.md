# Next Word Prediction with LSTM RNN and GRU RNN hi hello ev

## 📋 Project Overview
This project focuses on building a next word prediction model using two popular recurrent neural network (RNN) architectures - Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU). The model has been trained on the Shakespeare-Hamlet text from the NLTK Gutenberg corpus, so the predicted outputs will be in the context of Shakespearean language.

## Note
The model uses an RNN architecture to learn the patterns and dependencies in the Shakespeare-Hamlet text corpus. The LSTM and GRU units are designed to capture long-term dependencies in the data, which is crucial for accurate next word prediction.

## Features
* Uses a pre-trained LSTM model for next word prediction
* Interactive Streamlit web interface
* Real-time prediction based on user input

## 📚 Requirements
1. pandas
2. numpy
3. tensorflow
4. scikit-learn
5. tensorboard
6. matplotlib
7. streamlit
8. scikeras
9. nltk

## 💻 Installation
To run the project locally, follow these steps:

1. Clone the repository:

```cmd
git clone https://github.com/Yuvraj0014/Next-Word-Prediction-with-LSTM-RNN-and-GRU-RNN.git
Next-Word-Prediction-with-LSTM-RNN-and-GRU-RNN
```

2. Setup a virtual environment (optional but recommended)
```cmd
python -m venv venv
source venv/bin/activate  # For Linux/MacOS
venv\Scripts\activate  # For Windows
```

3. Install required dependencies
```cmd
pip install -r requirements.txt
```

4. Run the streamlit app
```cmd
streamlit run app.py
```

## Model Architecture
* The application uses an LSTM (Long Short-Term Memory) neural network trained on a text corpus
* The model learns to predict the next word in a sequence based on previous words

## Prediction Process
1. Input Processing
* User enters a text sequence
* The input is converted to numerical tokens using a pre-trained tokenizer
* Sequence is padded to match the model's expected input length

2. Prediction Steps
* Tokenize the input text
* Prepare the sequence for model input
* Use the LSTM model to predict the most likely next word
* Return the predicted word

## Key Functions
**predict_next_word()**: Core function that handles word prediction
* Converts text to token sequence
* Pads the sequence
* Uses the model to predict the next word

## Example Usage
* Input: "To be or not to"
* Predicted Next Word: Dynamically generated based on model training

## Limitations
* Prediction accuracy depends on model training data
* Works best with sequences similar to training corpus

## 🎯 Output Screen
![image](https://github.com/user-attachments/assets/45d180d8-9dfc-4fa3-a68c-5daf18677eeb)

## 🤖 Summary
The model uses an RNN architecture to learn the patterns and dependencies in the input text corpus. The LSTM and GRU units are designed to capture long-term dependencies in the data, which is crucial for accurate next word prediction.
During the training process, the model learns to map input sequences of words to their corresponding next words. When you provide an input sequence, the model uses its learned knowledge to predict the most likely next word based on the patterns it has identified in the training data.
