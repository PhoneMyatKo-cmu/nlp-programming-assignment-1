# Programming Assignment 1  
**Basic Text Preprocessing and Tokenization**  
**Phone Myat Ko Ko – 662115512**

## 1. Overview
This program performs text preprocessing and tokenization using three NLP frameworks:

- NLTK  
- TextBlob  
- spaCy  

The workflow includes:

1. Loading the `alice29.txt` corpus  
2. Cleaning and normalizing text  
3. Tokenization and stopword removal  
4. Writing cleaned text, token lists, and top-10 frequent words to output files  
5. Running performance benchmarking for each framework  
6. Visualizing execution time using matplotlib  

All generated files are stored in the `output/` directory.

---

## 2. Requirements

### 2.1 Environment
- Python 3.8+  
- Jupyter Notebook or Python interpreter  

### 2.2 Required Python libraries  
Install dependencies:

```bash
pip install nltk textblob spacy pandas matplotlib
```

Additionally, to use spacy , spaCy model needs to be downloaded
```
python -m spacy download en_core_web_sm
```
