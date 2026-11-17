# Deep Learning Practicals

Lab practicals for the Deep Learning course, implemented in Python (Jupyter notebooks).

| # | Practical | Libraries | Dataset needed |
|---|-----------|-----------|----------------|
| 1 | [McCulloch-Pitts Neuron](practical_01_mcculloch_pitts_neuron.ipynb) | NumPy | None |
| 2 | [NumPy, Pandas and Matplotlib](practical_02_numpy_pandas_matplotlib.ipynb) | Pandas, NumPy, Matplotlib | Titanic-Dataset .csv |
| 3 | [Neural Network on Iris with Different Activation Functions](practical_03_ann_iris_activation_functions.ipynb) | TensorFlow/Keras, scikit-learn, Pandas | IRIS.csv |
| 4 | [Feedforward Neural Network (PyTorch)](practical_04_feedforward_nn_iris_heart_titanic.ipynb) | PyTorch, scikit-learn, Pandas | heart.csv, Titanic-Dataset .csv (Iris is loaded from scikit-learn) |
| 5 | [Convolutional Neural Network (Cats vs Dogs)](practical_05_cnn_cats_vs_dogs.ipynb) | TensorFlow/Keras, scikit-learn, Matplotlib | Cats vs Dogs `train` image folder (Google Drive) |
| 6 | [RNN and LSTM for Stock Price Prediction](practical_06_rnn_lstm_stock_prediction.ipynb) | TensorFlow/Keras, yfinance, scikit-learn | Downloaded automatically with yfinance |
| 7 | [Sentiment Analysis with Bidirectional LSTM](practical_07_bilstm_imdb_sentiment.ipynb) | TensorFlow/Keras, scikit-learn, Pandas | IMDB-Dataset.csv |

## Outputs
The notebooks here are saved without outputs. The original run, with all outputs and plots, is in
[`DL_practicals_output.pdf`](DL_practicals_output.pdf).

## How to run
```bash
git clone <this-repo-url>
cd deep-learning-practicals
pip install -r requirements.txt
jupyter notebook
```

Datasets are not included in this repository. Download them (Titanic, Iris, Heart Disease, IMDB 50K Reviews, Cats vs Dogs from Kaggle) and place the CSV files next to the notebooks, or adjust the paths in the first cells.
Practical 5 was written for Google Colab (it mounts Google Drive), and Practical 6 needs an internet connection to download stock data.
