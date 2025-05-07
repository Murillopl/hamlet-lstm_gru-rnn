
# 📚 Hamlet LSTM/GRU RNN

This project implements recurrent neural network (RNN) models using **LSTM** and **GRU** architectures to predict the next word based on the text of *Hamlet* by William Shakespeare.  
The application was developed using **TensorFlow/Keras** and includes an interactive **Streamlit** interface.

## 🔗 Live Demo

- 🔮 **LSTM App:** [hamlet-lstm-app.streamlit.app](https://hamlet-lstm-app.streamlit.app/)
- 🤖 **GRU App:** [hamlet-gru-app.streamlit.app](https://hamlet-gru-app.streamlit.app/)

## 🔧 Technologies Used

- Python 3.11.7
- TensorFlow / Keras
- Streamlit
- Jupyter Notebook

## 📁 Project Structure

- `app_lstm.py`: Streamlit app using the LSTM model.
- `app_gru.py`: Streamlit app using the GRU model.
- `experiments_lstm.ipynb`: Notebook with LSTM training and evaluation.
- `experiments_gru.ipynb`: Notebook with GRU training and evaluation.
- `hamlet.txt`: Full Hamlet text used for training.
- `next_word_lstm.h5` / `next_word_gru.h5`: Trained model files.
- `tokenizer.pickle`: Tokenizer used during preprocessing.
- `requirements.txt`: Project dependencies.

## 🚀 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/Murillopl/hamlet-lstm_gru-rnn.git
cd hamlet-lstm_gru-rnn
```

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Run the app:

- For the LSTM model:

```bash
streamlit run app_lstm.py
```

- For the GRU model:

```bash
streamlit run app_gru.py
```

## 🧪 Experimental Results

The included notebooks provide insights into model training, loss curves, and predictions using both LSTM and GRU networks.

