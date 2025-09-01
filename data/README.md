# Data

This folder documents the dataset used for the **Organoid Literature NLP** project.

## Source
- ~20,000 abstracts retrieved from **PubMed** using API queries on the keyword *"intestinal organoids"*.  
- Time range: publications up to 2024.  
- Format: raw XML/JSON responses from the PubMed API.  

## Processing
- Extracted title, abstract, year, authors, journal, and metadata.  
- Preprocessing: lowercasing, tokenization, lemmatization, stopword removal.  
- Prepared text corpus for topic modeling and embeddings.

## Notes
- ⚠️ Raw PubMed files are **not included** in this repository due to size and copyright restrictions.  
- Only derived/cleaned versions were used in the notebooks.  
- To reproduce, you can query PubMed again using [Entrez API](https://www.ncbi.nlm.nih.gov/books/NBK25501/).
