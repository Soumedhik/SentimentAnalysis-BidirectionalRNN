# Sentiment Analysis with Bidirectional RNNs

## Overview

This repository contains a sentiment analysis project implemented using Bidirectional Recurrent Neural Networks (RNNs). The model is trained on a diverse dataset from Twitter and Reddit, providing accurate predictions of sentiment (Negative, Neutral, Positive) in text. The project includes preprocessing, model training, and evaluation code.

## Key Features

- **Bidirectional RNNs:** Utilizing Bidirectional Recurrent Neural Networks for improved sentiment analysis.

- **Dataset:** Training on a combination of Twitter and Reddit data for a diverse sentiment representation. 

- **Model Evaluation:** Metrics, including accuracy and confusion matrix, provided for model performance analysis.

- **Preprocessing:** Tokenization and padding of text data for input into the model.

## Model Architecture

The sentiment analysis model is built using TensorFlow and Keras. The architecture includes:

- Embedding Layer
- Bidirectional LSTM Layers 
- Dropout Layers
- Dense Layers

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Soumedhik/SentimentAnalysis-BidirectionalRNN.git
   cd SentimentAnalysis-BidirectionalRNN
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Model:**

   ```bash
   python run_sentiment_analysis.py
   ```

4. **Explore the Notebooks:**

  - `notebooks/`: Jupyter notebooks for in-depth analysis and visualization.

## Model File

The trained sentiment analysis model file (`model.h5`) is available in the [releases section](https://github.com/Soumedhik/SentimentAnalysis-BidirectionalRNN/releases).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.

## Acknowledgments

- Special thanks to [GloVe](https://nlp.stanford.edu/projects/glove/) for providing pre-trained word embeddings. 

## Contact

For any inquiries, please contact [Soumedhik](mailto:soumedhikbharati@gmail.com).



```
