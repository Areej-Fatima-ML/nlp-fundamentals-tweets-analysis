# nlp-fundamentals-tweets-analysis
# NLP Fundamentals – Text Processing, Embeddings & LLMs

A comprehensive NLP project covering text preprocessing, text representation, word embeddings, language models, and generative vs. discriminative approaches, applied to a Twitter/Tweets sentiment dataset.

## Objective

- Understand core NLP preprocessing techniques
- Build and compare text representations
- Explore embeddings and language models
- Analyze generative vs. discriminative approaches
- Experiment with modern LLMs

## Dataset

- **Source:** Twitter/Tweets Sentiment dataset (public)
- **Content:** Raw tweets used for text cleaning, representation, and classification tasks

## Project Workflow

### Part 1: Text Processing & Normalization
- **Raw Text Cleaning:** Lowercasing, punctuation removal, optional number removal; compared original vs cleaned text
- **Tokenization & Stopwords:** Tokenized cleaned text, removed stopwords, compared before/after and identified wrongly removed words
- **Stemming vs Lemmatization:** Applied both, compared output differences and linguistic correctness; reflected on best use case for search engines, chatbots, and text classification

### Part 2: Text Representation
- **N-gram Modeling:** Generated unigrams, bigrams, and trigrams; identified most frequent n-grams and analyzed how context improves with higher N
- **Vectorization Techniques:** Applied Bag of Words, Count Vectorizer, and TF-IDF; compared vocabulary size, feature importance, and sparsity

### Part 3: Word Embeddings
- Trained/used pre-trained embeddings (Word2Vec / GloVe / FastText)
- Found similar words and explored word analogies (e.g., king - man + woman ≈ queen)

### Part 4: Language Models
- **N-gram Language Model:** Estimated sequence probabilities, predicted next word, compared unigram vs bigram predictions
- **Mini LLM Conceptual Design:** Designed a simple LLM pipeline (tokenization, embedding layer, sequence modeling, output prediction)

### Part 5: Generative AI & LLMs
- Explored open-source (LLaMA/Mistral/GPT4All) and closed-source (ChatGPT/Claude) models
- Performed text generation, summarization, and question answering
- Compared quality, speed, cost, and control across models
- Designed prompts for summarization, classification, and creative writing (prompt engineering)

### Part 6: Classification
- **Discriminative approach:** Logistic Regression / SVM
- **Generative approach:** Naive Bayes / LLM prompting
- Compared accuracy, interpretability, and data requirements between approaches

## Tools & Libraries

- Python 3.x
- pandas, numpy
- NLTK / spaCy
- scikit-learn
- Gensim (Word2Vec/GloVe/FastText)
- Open-source & closed-source LLM APIs

## How to run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Ensure the Twitter/Tweets dataset is available (download link or path).
3. Run all cells in order.

## Notes

- Includes written reflections and comparisons for each task as required
- Includes prompt engineering examples for summarization, classification, and creative writing
