# Sentiment-Analysis

# 🎬 Sentiment Analysis using LSTM & GloVe

A Deep Learning-based **Sentiment Analysis** project that classifies movie reviews as **Positive** or **Negative** using an **LSTM (Long Short-Term Memory)** neural network with **100-dimensional GloVe word embeddings**.

## 📌 Project Overview

This project uses the **IMDB Movie Reviews dataset containing 50,000 labeled reviews**. The text data is cleaned and converted into numerical sequences before being passed to an LSTM model.

The model uses pre-trained **GloVe embeddings** to represent words as numerical vectors and an **LSTM layer** to learn the contextual patterns in movie reviews.

## 🚀 Features

* Text preprocessing and cleaning
* HTML tag and punctuation removal
* Tokenization and sequence conversion
* Sequence padding
* 100-dimensional GloVe word embeddings
* LSTM-based sentiment classification
* Model training and validation
* Test dataset evaluation
* Prediction on unseen movie reviews
* Training accuracy and loss visualization

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Scikit-learn
* GloVe Word Embeddings
* Jupyter Notebook

## 🧠 Model Architecture

The model consists of:

```text
Input Movie Review
       ↓
Text Preprocessing
       ↓
Tokenization
       ↓
Sequence Padding
       ↓
GloVe Embedding Layer (100D)
       ↓
LSTM Layer (128 Units)
       ↓
Dense Layer (Sigmoid)
       ↓
Positive / Negative
```

### Model Configuration

* Vocabulary size: 5,000 words
* Embedding dimension: 100
* Maximum sequence length: 100
* LSTM units: 128
* Optimizer: Adam
* Loss function: Binary Cross-Entropy
* Epochs: 6
* Batch size: 128
* Validation split: 20%

## 📂 Dataset

The project uses the **IMDB Dataset**, containing:

* **50,000 movie reviews**
* **25,000 positive reviews**
* **25,000 negative reviews**

Each review is labeled as either `positive` or `negative`.

## 🔄 Workflow

1. Load the movie review dataset.
2. Check for missing values and dataset dimensions.
3. Clean the review text.
4. Convert sentiment labels into numerical values.
5. Split the dataset into training and testing sets.
6. Tokenize the reviews.
7. Convert text into sequences.
8. Apply padding to make sequences equal in length.
9. Load pre-trained GloVe embeddings.
10. Create the LSTM model.
11. Train and validate the model.
12. Evaluate the model on unseen test data.
13. Visualize accuracy and loss.
14. Test the model with a new movie review.

## 📁 Repository Structure

```text
Sentiment-Analysis/
│
├── Sentiment Analysis using LSTM and GloVe(Global Vectors) Embeddings..ipynb
├── LICENSE
├── .gitignore
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Sentiment-Analysis.git
cd Sentiment-Analysis
```

### 2. Install required libraries

```bash
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn jupyter
```

### 3. Download GloVe Embeddings

Download the **GloVe 6B 100-dimensional embeddings** and update the file path in the notebook.

### 4. Open the notebook

```bash
jupyter notebook
```

Open:

```text
Sentiment Analysis using LSTM and GloVe(Global Vectors) Embeddings..ipynb
```

Run the notebook cells sequentially.

## 📊 Results

The trained LSTM model is evaluated on unseen test data and is also used to predict the sentiment of a new movie review.

The notebook includes visualizations for:

* Training vs. validation accuracy
* Training vs. validation loss
* Sentiment distribution

## 🔮 Example Prediction

The model can take a new movie review as input and classify it as:

```text
Positive Review
```

or

```text
Negative Review
```

## 📚 Concepts Covered

* Natural Language Processing (NLP)
* Text preprocessing
* Tokenization
* Word embeddings
* GloVe
* Recurrent Neural Networks (RNN)
* LSTM
* Binary classification
* Deep Learning model evaluation

## 👨‍💻 Author

**Puneet**

B.Tech CSE Student

---

⭐ If you find this project useful, consider giving the repository a star!
