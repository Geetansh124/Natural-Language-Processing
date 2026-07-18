# Natural Language Processing (NLP) Projects

This repository contains a collection of Jupyter Notebooks demonstrating various Natural Language Processing (NLP) concepts and techniques. It serves as a practical guide and portfolio for different NLP tasks, ranging from basic text preprocessing to more advanced topics like text classification and exploring real-world datasets like Quora Question Pairs.

## 📁 Repository Structure

The repository is organized into the following key sections:

### 1. Text Preprocessing
* **`text_preprocessing.ipynb`**: Covers fundamental text cleaning techniques such as removing HTML tags, punctuation, and URLs, handling emojis, stemming (PorterStemmer), and removing stopwords.
* **`feature-extraction.ipynb`**: Demonstrates how to extract meaningful features from raw text data.
* *Dataset*: Uses the `IMDB Dataset.csv` for practical examples.

### 2. POS Tagging
* **`pos-tagging.ipynb`**: Explores Part-of-Speech (POS) tagging, a critical NLP task for understanding the grammatical structure of sentences, utilizing libraries like `spacy`.

### 3. Text Classification
* **`text-classification.ipynb`**: Focuses on classifying text into different categories (e.g., sentiment analysis).
* **`word2vec.ipynb`**: Implements Word2Vec, a popular technique for generating word embeddings that capture semantic relationships between words.
* *Dataset*: Uses the `IMDB Dataset.csv` for training and testing classification models.

### 4. Quora Question Pairs
* **`ini_eda.ipynb`**: Initial Exploratory Data Analysis (EDA) on the Quora Question Pairs dataset, utilizing libraries like pandas, matplotlib, and seaborn to visualize data distributions and understand the problem space.
* **`only_bow.ipynb`**: Applies a Bag-of-Words (BoW) approach to identifying duplicate questions.

## 🛠️ Prerequisites and Installation

To run the notebooks in this repository, you will need Python installed along with several data science and NLP libraries.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
   *(Note: Replace the URL with your actual repository URL)*

2. **Install Required Libraries:**
   You can install the common dependencies using `pip`. The primary libraries used across the notebooks include:
   ```bash
   pip install pandas numpy scikit-learn nltk spacy matplotlib seaborn emoji jupyter
   ```

3. **Download Language Models (if required):**
   Some notebooks use `spacy` or `nltk` which might require downloading specific language models or corpora.
   ```bash
   python -m spacy download en_core_web_sm
   python -c "import nltk; nltk.download('stopwords')"
   ```

## 🚀 Usage

1. Start a Jupyter Notebook server in the root of the cloned directory:
   ```bash
   jupyter notebook
   ```
2. Navigate to the desired folder and open the notebook you wish to explore.
3. Ensure that datasets like `IMDB Dataset.csv` are present in the respective directories as indicated by the folder structure before running the cells.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
