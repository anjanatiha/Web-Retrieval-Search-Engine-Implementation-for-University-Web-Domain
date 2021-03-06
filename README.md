# Web Retrieval Engine Implementation for University Domain

##### Domain             : Information Retrieval, Web Retrieval, Web Search
##### Sub-Domain         : Search Engine, Natural Language Processing
##### Techniques         : Vector Space Modeling, Query Operations, Relevance Ranking, Evaluation.

### Description:	
1. Developed vector space model based web retrieval engine for University of Memphis domain (memphis.edu).
2. Crawled and preprocessed 10, 000 web pages and docs (text, pdf, docx and pptx) from University of Memphis domain.
3. Built modules - web crawler (incremental), text preprocessor (removes- (markup, metadata, uppercase, digits, punctuation, space,  stop words), tokenize, stem from raw HTML/docs), Indexer (doc-url, doc-term, term-doc), TF-IDF vector generator, webpage relevance ranker and performance evaluator (F1, precision, recall).
4. Used TF-IDF vector space model for web page matching and cosine similarity function for web page ranking.

#### Web Retrieval Engine Graphical Interface: 
<kbd>
<img src=https://github.com/anjanatiha/Web-Retrieval-Engine/blob/master/Report/images/main.png >
</kbd>
  
#### Sample Search:
<kbd>
<img src=https://github.com/anjanatiha/Web-Retrieval-Engine/blob/master/Report/images/search.png>
</kbd>

### Instruction for Web Crawling and Vector Space Model Building:
1. Go to search_engine/search_engine_website
2. Run inverse_document_indexer_final function in "search_engine.py" file to collect documents(html/php/txt/doc/docx/ppt/pptx) using web crawler.
3. This builds vector space model with inverse document indexer and TF-IDF vector for all collected documents.
4. Option available to change to website by changing the url value in "search_engine.py".
5. Enter query term for retrieving or searching within collected web documents.


### Instruction for Running Query on Web Interface:
1. To run Django server go to ”search_engine/search_engine_website”
2. Open command prompt in the current directory of manage.py and type manage.py preceded
by python.exe location and python in the follwoing manner:
  1. C:\Users\Anjana\Anaconda3\pythonmanage.pyrunserverserver (format->locationforpython.exe+python+manage.py)
3. To view web interface for search engine go to http://127.0.0.1:8000/

### Django Installation Steps:
1. Install pip for python.
2. Move to python directory or scripts directory in Anaconda.
3. Please enter ”pip install Django” for installing Django.

##### Languages   : Python
##### Tools/IDE   : Anaconda, Django
##### Libraries   : Django
##### Duration    : August - December 2017

Current Version  : v1.0.0.0

Last Update      : 12.01.2017
