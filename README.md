# Next-Word Prediction System using LSTM & GRU

## Overview
This project is a **Next-Word Prediction System** built using **LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit)**. The model is trained on textual data to predict the next word based on a given sequence of words. The system is deployed using **Streamlit**, providing an interactive UI for users to input text and receive predictions.

## Features
- Implements **LSTM & GRU** for sequence modeling
- Uses **TensorFlow** and **Keras** for deep learning
- Tokenizes and preprocesses text input using **NLTK** and **Keras Tokenizer**
- Deploys as a **web app using Streamlit**
- Provides real-time word prediction based on user input

## Installation
### Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### Clone the Repository
```sh
git clone https://github.com/yourusername/next-word-prediction.git
cd next-word-prediction
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage
### Run the Application
```sh
streamlit run app.py
```
Open your browser and go to `http://localhost:8501/` to use the application.

### Input Example
User enters: `To be or not to`
Predicted Next Word: `be`

## File Structure
```
next-word-prediction/
│── app.py                 # Streamlit web app
│── next_word_lstm.h5      # Trained LSTM model
│── tokenizer.pickle       # Tokenizer for text preprocessing
│── experiments.ipynb      # Model training experiments
│── requirements.txt       # Project dependencies
│── README.md              # Project documentation
```

## Technologies Used
- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **NLTK**
- **NumPy, Pandas**

## Future Enhancements
- Implement a **hybrid model combining LSTM and GRU**
- Train on a **larger dataset for improved accuracy**
- Optimize **performance and model size** for faster predictions
- Add **support for multiple languages**

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


