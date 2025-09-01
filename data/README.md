# Data

This folder contains the dataset used for the **Organoid Literature NLP** project.

## File
- **organoid_abstracts_clean.csv**  
  - Columns: `title`, `abstract`, `year`, `authors`, `journal`, `pmid`  
  - Preprocessed text (lowercased, lemmatized, stopwords removed)  
  - Ready for use in topic modeling and embeddings  

## Source
- ~20,000 abstracts originally retrieved from **PubMed** using API queries on the keyword *"intestinal organoids"*.  
- Time range: publications up to 2024.  

## Notes
- ⚠️ Raw PubMed data is **not included** in this repository due to size and copyright restrictions.  
- This CSV is the **cleaned version** used in the notebooks.  
- To reproduce from scratch, query PubMed again using [Entrez API](https://www.ncbi.nlm.nih.gov/books/NBK25501/).
