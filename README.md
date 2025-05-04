## Discovering Wrongdoing from the Enron Email Corpus

This repository contains the code and analysis for identifying financial fraud evidence in the Enron email corpus.  
Focus: using NLP, keyword filtering, and social network analysis to uncover signs of financial manipulation.

### Project Overview

- **Dataset:** Public Enron email corpus (~250,000 emails).
- **Preprocessing:**  
  - Keyword-based email filtering using ElasticSearch.  
  - NLP stopword removal and text cleaning.
- **Analysis:**  
  - Social Network Analysis to identify influential employees.  
  - TF-IDF scoring and K-Means clustering (visualized with PCA).  
  - Word Cloud generation for cluster insights.
- **Findings:**  
  - Identified 5 emails containing strong indicators of fraudulent financial activities (e.g., revenue inflation, balance sheet manipulation, off-balance-sheet transactions).

### Note

Large data files (email corpus and ElasticSearch index) are **NOT included** in this repository.  
Please contact me for details if needed.

### Status

Code and final analysis available. Data files excluded.

---

#### 🔒 Copyright & Usage Notice

© Ziyi Song. All rights reserved.

The code, documentation, and all associated content in this repository are the intellectual property of the author and may not be copied, redistributed, or used for commercial purposes without prior written consent.  
This repository is shared publicly for educational and portfolio purposes only.  
For any inquiries regarding usage, please contact the author directly.
