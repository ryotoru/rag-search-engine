# rag-search-engine
This project is a copy of [MinSearch](https://github.com/alexeygrigorev/minsearch). 

A minimalistic search engine that provides both text-based and vector-based search capabilities. The library provides three implementations:

1. `Index`: A basic search index using scikit-learn's TF-IDF vectorizer for text fields
2. `AppendableIndex`: An appendable search index using an inverted index implementation that allows for incremental document addition
3. `VectorSearch`: A vector search index using cosine similarity for pre-computed vectors

## Features

- Text field indexing with TF-IDF and cosine similarity
- Vector search with cosine similarity for pre-computed embeddings
- Keyword field filtering with exact matching
- Field boosting for fine-tuning search relevance (text-based search)
- Stop word removal and custom tokenization
- Support for incremental document addition (AppendableIndex)
- Customizable tokenizer patterns and stop words
- Efficient search with filtering and boosting

__Note:__ this is a toy example for illustrating how relevance search works. It's not meant to be used in production.