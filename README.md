# Organoid Literature NLP — Research Trends Analysis

**One-liner:** Analyzing 20k+ PubMed abstracts on intestinal organoids using NLP to uncover research themes and trends over time.

## Context
This project was developed as part of the **Data Science Bootcamp at CodeOp**.  
Scientific research on intestinal organoids has grown rapidly, but keeping track of trends across thousands of publications is challenging.  
This project uses **Natural Language Processing (NLP)** to analyze PubMed abstracts, identify main research topics, and visualize their evolution.

## Dataset
- ~20,000 PubMed abstracts (retrieved via API queries on "intestinal organoids").  
- Processed: tokenization, lemmatization, stopword removal.

⚠️ Raw data files are **not included** in this repository due to size and copyright restrictions.  
See `data/README.md` for details about sources and processing.

## Methods
- **EDA:** word clouds, frequency analysis, n-grams  
- **Topic Modeling:** Latent Dirichlet Allocation (LDA)  
- **Embeddings:** Word2Vec / Doc2Vec for clustering and semantic similarity  
- **Visualization:** heatmaps, t-SNE projections, temporal trend plots

## Notebooks
- `data_collection.ipynb` → Retrieves PubMed abstracts on “intestinal organoids” and saves a cleaned CSV.  
- `organoid_NLP.ipynb` → Main analysis: exploratory data analysis, topic modeling (LDA), embeddings, and trend visualization.

## Results
- Identified main themes (e.g., tissue engineering, disease modeling, regenerative medicine).  
- Visualized temporal trends in research focus.  

## Repository Info
- **Description:** NLP analysis of organoid-related literature to extract topics and research trends.  
- **Topics:** `nlp`, `text-mining`, `literature-analysis`, `organoids`, `biomedicine`
