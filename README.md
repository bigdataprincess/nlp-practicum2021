# Machine Learning Guild - NLP Practicum

Textbook: 
- [Speech and Language Processing (SLP):](https://web.stanford.edu/~jurafsky/slp3/)
- [SLP YouTube Videos:](https://www.youtube.com/playlist?list=PLQiyVNMpDLKnZYBTUOlSI9mi9wAErFtFm)


# Setup and Installation
- You'll be able to follow along without installing Python on your computer by viewing the Jupyter notebooks in the repo. You should also be able to run all code except for lesson one using the Google Colab buttons.
- The repository has been built for Windows computers. Some packages may be incompatible with Macs.
- Environment setup instructions: https://www.youtube.com/watch?v=sUUWLBmj7Xc&feature=youtu.be
- For lesson one, you will want to use environment_nlp-course-small.yml for a fast installation.
- Config.ini: You will need to change two lines in the config.ini file under [USER]. Change the text following "USERNAME:" to your username and "RAW_DATA:" to the file path to the raw data folder within the repository.


# LESSONS

### 0. Configuration (Pre-work)
*  Topics: course overview, git bash, python config.ini files, conda virtual environments
*  Technology: git bash, configparser, conda
*  Homework: use the command line to search data among 1000's of server configuration files

### 1. Text Extraction
*  Topics: Extract text from docx, pdf, and image files
*  Technology: docx, PyPDF2, pdfminer.six, subprocess, pytesseract
*  Homework: structure the annual reports into sections
*  Supplementary Material: watch lesson_databases videos

### 2. Text Preprocessing
*  Topics: POS tagging, dependency parsing, rule-based matching, phrase dectection
*  Technology: SpaCy, gensim
*  Prework: Read section 2.1-2.4 SLP and/or 2.1-2.5 SLP videos
, section 8.1-8.3 SLP, and chapter 5 [Collocations](https://nlp.stanford.edu/fsnlp/promo/colloc.pdf)
*  Supplementary Material: watch lesson_automation videos

### 3. Text Vectorization (count-based methods)
*  Topics: vector space model, TFIDF, BM25, Co-occurance matrix
*  Technology: scikit-learn
*  Prework: Read section 6.1-6.6 SLP
*  Supplementary Material: watch lesson_object_oriented_python

### 4. Dimensionality Reduction
*  Topics: PCA, latent semantic indexing (LSI), latent dirichlet allocation(LDA), topic coherence metrics
*  Technology: scikit-learn, gensim
*  Prework: Read [TamingTextwiththeSVD](https://www.semanticscholar.org/paper/Taming-Text-with-the-SVD-Albright/7d552470ef3ebb49593b8cc94e4e063b30f650ab)

### 5. Word Embeddings 
* Topics: Word2Vec, GloVe, FastText
* Technology: scikit-learn, gensim
* Prework: Read section 6.8-6.13 SLP, [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf) & [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/pdf/1310.4546.pdf)

### 6. Deep Learning for NLP 1
* Topics: Neural networks with word embeddings
* Technology: keras, gensim, FLAIR (pytorch)
* Prework: Read [NLP (Almost) from Scratch](http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf) and [A Primer on Neural Network Models for Natural Language Processing](https://arxiv.org/pdf/1510.00726.pdf)

### 7. Deep Learning for NLP 2
* Topics: Neural networks with word embeddings, Contextual Word Embeddings
* Technology: keras, gensim, FLAIR (pytorch)
* Prework: Read [NLP (Almost) from Scratch](http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf) and [A Primer on Neural Network Models for Natural Language Processing](https://arxiv.org/pdf/1510.00726.pdf)

### 8. Text Similarity
*  Topics: cosine similarity, distance metrics, l1 and l2 norm, recommendation engines
*  Technology: scikit-learn, SpaCy, gensim
*  Prework: Read section 2.5 SLP and/or 2.1-2.5 SLP videos


# SUPPLEMENTARY MATERIAL

### Automation
*  Topics: automate the process to collect data from https://www.annualreports.com
*  Technology: requests, Jupyter Notebooks, BeautifulSoup, Scrapy
*  Homework: automate the process to identify and download company 10-K annual reports

### Databases
*  Topics: use sqlalchemy to create and populate a database, locally and on AWS
*  Technology: sqlalchemy, sqllite, AWS RDS (MySQL)
*  Homework: create and populate a database with sqlalchemy

### Object Oriented Python
*  Topics: reconstruct scikit-learn's CountVectorizer codebase
*  Technology: scikit-learn, object oriented Python
