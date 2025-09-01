# Data

This folder contains the dataset used for the **Organoid Literature NLP** project.

## File
- **organoid_abstracts_clean.csv**  
  - Columns: `title`, `abstract`, `year`, `authors`, `journal`, `pmid`  
  - Preprocessed text (lowercased, lemmatized, stopwords removed)  
  - This is the version used in the `organoid_NLP.ipynb` analysis.

## Source
- Abstracts originally retrieved from **PubMed** using queries on *"intestinal organoids"*.  
- The collection process is documented in the notebook `data_collection.ipynb`.  
- Time range: publications up to 2024.  

## Notes
- ⚠️ Raw PubMed files are **not included** in this repository due to size and copyright restrictions.  
- The CSV file is a **cleaned subset** prepared for educational purposes during the CodeOp Data Science Bootcamp.  
- To reproduce the dataset, rerun `data_collection.ipynb` with your own PubMed API credentials (Entrez).
