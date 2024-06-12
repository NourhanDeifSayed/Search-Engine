# Search-Engine
Key Preprocessing Steps:

Data Handling: Utilized Pandas for efficient data manipulation.

Text Processing:

Tokenization: Implemented using NLTK.

Stopwords Removal: Used NLTK stopwords to filter out common words.

Stemming: Applied PorterStemmer to reduce words to their base form.

Cleaning: Custom function to remove URLs, special characters, and unnecessary white spaces from text.

Boolean Retrieval and Inverted Index:

The core of our search functionality is powered by Boolean retrieval and inverted index methods using PyTerrier. This ensures precise and relevant search results by efficiently indexing and retrieving documents.

Query Processing:

We preprocess queries similarly to how we process documents:

Remove stopwords and special characters.

Tokenize and stem the text to ensure consistency.

Example: Cleaned and stemmed queries to match the indexed documents better.

Ranking Techniques:

We used TF-IDF and BM25 ranking techniques to enhance the accuracy of search results. TF-IDF helps assess the importance of words within documents, while BM25 provides an effective information retrieval model.

Query Expansion and Comparison:

We utilized query expansion techniques to enhance search results. For instance, expanding the original query with related terms improves the relevance of retrieved documents. We compare search results before and after expansion to validate the improvement.

Embedding Features:

Explored embedding features to enhance document understanding:

Leveraged TensorFlow and TensorFlow Hub for embedding generation.

Extracted specific embedding vectors to improve the search engine’s precision.
