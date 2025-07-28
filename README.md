# Sentimental Analysis using RNN

This project performs **Sentimental Analysis** on textual data using a **Recurrent Neural Network (RNN)**. The model is built and trained using Python in a Jupyter Notebook.

## Project Structure

```
SentimentalAnalysis/
│
├── rnn.ipynb            # Main Jupyter notebook for training and evaluation
├── data/                # (Optional) Folder for your datasets
├── .gitignore           # Git ignored files and folders
└── README.md            # Project documentation
```

## Features

- Preprocessing of text data (tokenization, padding)
- Word embedding using Keras `Embedding` layer
- Sequence modeling using RNN (SimpleRNN/LSTM/GRU)
- Model training and evaluation
- Prediction and sentiment classification

## How to Run

### Requirements

- Python 3.7+
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib / Seaborn (optional for visualizations)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/LalithaSriPani21/SentimentalAnalysis.git
   cd SentimentalAnalysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `rnn.ipynb` and run the cells step-by-step.

## Example Output

The notebook displays the training accuracy and loss, along with sentiment predictions on test sentences.

## ✍️ Author

[LalithaSriPani](https://github.com/LalithaSriPani21)

