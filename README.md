# next-word-prediction-lstm-gru-streamlit
Next Word Prediction using LSTM and GRU Models. This project takes a sequence of words and predicts the next word using a trained deep learning model. The app is built with Streamlit and allows users to input text and get predictions instantly.

# Next Word Prediction with LSTM and GRU

This project demonstrates a **Next Word Prediction** model using **LSTM** (Long Short-Term Memory) and **GRU** (Gated Recurrent Unit) neural networks. The app allows users to input a sequence of words and predicts the next word based on the trained model.

## Features
- Predicts the next word in a sentence.
- Uses LSTM and GRU models for sequence prediction.
- Built with **Streamlit** for an interactive user interface.

## How it Works
1. The model was trained on text data using **LSTM** architecture.
2. It uses a **tokenizer** to convert input text into sequences.
3. The model predicts the next word based on the input sequence.
4. The sequence is padded to match the input shape required by the model.

## Technologies Used
- **TensorFlow/Keras**: For building and training the LSTM model.
- **Streamlit**: For the web interface.
- **Pickle**: To load the tokenizer.

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/next-word-prediction.git
   cd next-word-prediction
   ```
 2.Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
  3.Run the Streamlit app:
   ```bash
     streamlit run app.py
   ```
  4.Input a sequence of words and click "Predict Next Word."
  
## Files in the Repository
  - next_word_lstm.h5: Pretrained LSTM model.
  - tokenizer.pickle: Tokenizer used for encoding text sequences.
  - app.py: Main application script to run the Streamlit app.
## Future Improvements
  - Integrate GRU model for comparison with LSTM.
  - Expand the app to handle larger text sequences and add more flexibility in input size.
  - Deploy the model to the cloud for public access.
## Credits
  - This project was built by Mahmoud Abdelhamid as part of exploring AI-driven text prediction models.
