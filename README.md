# Article Classification Using NLP & Machine Learning

## Project Overview
This project focuses on building an **Article Classification System** using multiple Natural Language Processing (NLP) and Machine Learning techniques.  
The dataset contains research article text along with category labels, and the goal is to classify articles into their correct research domains.

The project also extracts five major insights from the dataset:

1. **Topic Trends** – Identifying which research areas are most common.  
2. **Keyword Analysis** – Finding frequently occurring terms in each category.  
3. **Venue Insights** – Understanding where different types of articles are published.  
4. **Model Performance Comparison** – Comparing BoW, Word2Vec, GloVe, and BERT.  
5. **Semantic Clustering** – Grouping papers based on meaning to discover hidden patterns.

##  Features
- Preprocessing and cleaning of text data  
- Handling large JSON article dataset  
- Label encoding and exploratory analysis  
- Implementation of four NLP-based models:
  - TF-IDF + Logistic Regression  
  - Word2Vec embeddings  
  - GloVe embeddings  
  - BERT Transformer model  
- Performance metrics (accuracy, precision, recall, F1-score)  
- Visualizations and insight extraction  

##  Repository Structure
- `article_classification.ipynb` — Full project notebook  
- `dataset.json` — Article dataset in JSON format  
- `models/` — Optional folder for saved models  
- `bert_results/` — Outputs from BERT  

##  Tech Stack
- Python  
- Google Colab / Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Gensim  
- HuggingFace Transformers  
- Matplotlib, Seaborn  

##  Use Case
This project can be used for:  
- Research article categorization  
- Identifying academic trends  
- Topic discovery and clustering  
- Comparing classical and deep learning NLP methods  
- Building indexing or recommendation systems for research platforms  

##  License
This project is licensed under the MIT License.
