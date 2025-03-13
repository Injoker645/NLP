# PubMed Paper Tagger 🏥🔍  

## Overview  
Medical research papers, especially older ones, often lack proper tagging, making it harder to find relevant studies. This project develops a **Natural Language Processing (NLP) model** to predict missing tags for research papers on PubMed. Using **BERT-based** and **Sequential NLP models**, we aim to improve the discoverability and accessibility of medical research.  

## Approach  
- **Data Collection & Preprocessing**: Scraped PubMed data, cleaned and structured it for model training.  
- **Model Development**: Implemented two NLP approaches:  
  - **BERT-based Model** (`BERT Model.ipynb`)  
  - **Sequential NLP Model** (`PubMed Paper Tagger Sequential.ipynb`)  
- **Evaluation**: Using **Precision, Recall, and F1-score** to measure model performance.  

## Files  
- `BERT Model.ipynb` – Implements a BERT-based tag predictor.  
- `PubMed Paper Tagger Sequential.ipynb` – Uses a simpler sequential NLP model.  
- `Data Importing.ipynb` – Web scraper and data preprocessor.  
- `Covid_Papers.csv` – Sample dataset used for training/testing.  
- `PubMed_Tagger_Proposal.pdf` – Full project proposal.  

## View Notebooks  
Since Jupyter Notebooks aren't rendered on GitHub, you can view them via **nbviewer**:  
- [View BERT Model.ipynb](https://nbviewer.org/github/Injoker645/NLP/blob/main/PubMed_Tagger/BERT%20Model.ipynb)  
- [View PubMed Paper Tagger Sequential.ipynb](https://nbviewer.org/github/Injoker645/NLP/blob/main/PubMed_Tagger/PubMed%20Paper%20Tagger%20Sequential%20.ipynb)  
- [View Data Importing.ipynb](https://nbviewer.org/github/Injoker645/NLP/blob/main/PubMed_Tagger/Data%20Importing.ipynb)  

## Read the Full Proposal 📄  
[👉 Click here to view the full proposal](https://nbviewer.org/github/Injoker645/NLP/blob/main/PubMed_Tagger/PubMed_Tagger_Proposal.pdf)  

## Potential Impact  
This project can enhance medical research accessibility by:  
✅ Improving **searchability** of older research papers.  
✅ Enabling **better information retrieval** for researchers & professionals.  
✅ Supporting **medical knowledge graphs** and **gap analysis** in research.  

Stay tuned for updates! 🚀
