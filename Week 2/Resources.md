# WEEK 2:

In the second week, we will explore Natural Language Processing (NLP), a field that focuses on the interaction between computers and humans using natural language. Understanding the fundamentals of text processing, language modeling, and sentiment analysis will be crucial for tasks such as chatbots, language translation, and text summarization.

## NLP (Natural Language Processing)
**CONTENTS**

- Regular Expressions
- Word Embeddings 
- Text Preprocessing
- Sentiment Analysis

### Regular Expressions

Regex is a rule-based, pattern-matching tool used to find, extract, or manipulate strings in text. It uses a defined syntax to search for patterns in text. For example, \d+ matches one or more digits, and \bcat\b matches the word "cat" but not "category.

- [**Python Regex**](https://www.w3schools.com/python/python_regex.asp)
- [**Video Tutorial**](https://www.youtube.com/watch?v=ZfQFUJhPqMM)

### Word Embeddings

Neural networks cannot process words directly; they deal only with numerical vectors and their computations. To feed text as input to a neural network, we need to convert it into vector form using word embeddings. Various techniques (TF-IDF, Skip-gram, CBOW) and implementations (Glove, FastText, etc.) exist for this purpose.

Read these articles:

- [**Brief conceptual overview**](https://www.geeksforgeeks.org/word-embeddings-in-nlp/) (_Must read_)
- [**TF-IDF**](https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/)
- [**CBOW**](https://www.geeksforgeeks.org/continuous-bag-of-words-cbow-in-nlp/)
- [**Skipgram**](https://www.geeksforgeeks.org/implement-your-own-word2vecskip-gram-model-in-python/)

### Text Preprocessing

Text preprocessing in NLP is essential to clean and transform raw text data, addressing issues like irrelevant characters, formatting, and inconsistencies to ensure its suitability for analysis by machine learning models.

**Main Topics to Keep in Mind:**

- Tokenization
- Lowercase conversion
- Stopwords removal
- Stemming
- Lemmatization

**RESOURCES**

- [**Detailed guide**](https://www.analyticsvidhya.com/blog/2021/06/text-preprocessing-in-nlp-with-python-codes/) (Recommended)
- [**Youtube Video**](https://www.youtube.com/watch?v=nxhCyeRR75Q), focusing more on post-cleanup steps like tokenization, stemming, and lemmatization
- [**Stemmig vs Lemmatization**](https://www.ibm.com/topics/stemming-lemmatization#:~:text=The%20practical%20distinction%20between%20stemming,be%20found%20in%20the%20dictionary)

### Sentiment Analysis

Sentiment analysis in NLP involves determining the emotional tone or subjective information expressed in a piece of text, helping identify and quantify sentiments such as positive, negative, or neutral attitudes.

- [Short intro](https://www.geeksforgeeks.org/what-is-sentiment-analysis/)

### NLTK vs spaCy

NLTK is versatile and suitable for learning and experimenting with various NLP concepts, making it popular in academic and research settings. spaCy, with its emphasis on speed and ease of use, is favored in the industry for developing efficient and scalable NLP applications. The choice between NLTK and spaCy depends on the specific needs of a project and the user's goals, whether it be educational exploration or real-world application development.

### TEXT PROCESSING WITH NLTK

**RESOURCES**

 - [**NLTK Video Tutorial**](https://www.youtube.com/playlist?list=PLS1QulWo1RIZDws-_0Bfw5FZFmQJWtMl1) - The first 4 videos will suffice.
 - [**Official Documentation for NLTK**](https://www.nltk.org/) - Always go through the documentation to understand and fix your errors.


### TEXT PROCESSING WITH SPACY

**RESOURCES**

- [**Spacy Documentation**](https://spacy.io/usage/spacy-101)
- [**Spacy Video Tutorial**](https://youtu.be/THduWAnG97k)

**Main Topics to Keep in Mind:**

- Tokenization
- Parts of Speech Tagging
- Named Entity Recognition

Feel free to reach out if you have any questions or need further clarification on any topic.
