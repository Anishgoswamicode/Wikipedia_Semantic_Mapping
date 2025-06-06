📚 Wikipedia Semantic Mapping using Sentence-BERT and UMAP Clustering

This project explores the hidden semantic structure of Wikipedia topics using advanced NLP and unsupervised learning techniques. It retrieves topic descriptions from Wikipedia, generates dense vector embeddings using Sentence-BERT, and uses UMAP and DBSCAN to visualize and discover clusters of semantically related topics.

🔍 Overview
1. Sentence Embeddings: Contextual embeddings generated using ‘sentence-transformers’ (Sentence-BERT).
2. Dimensionality Reduction: UMAP projects high-dimensional vectors to 2D space for visual exploration.
3. Clustering: DBSCAN detects dense topic clusters without requiring a predefined number of clusters.
4. Keyword Extraction: KeyBERT is used to summarize each cluster with meaningful keywords.
5. Visualization: Matplotlib is used to create clear, labeled plots of topic groupings.

🧠 Techniques Used
1. ✅ BERT-based semantic embeddings (`sentence-transformers`)
2. ✅ Unsupervised learning (UMAP + DBSCAN)
3. ✅ Clustering and keyword interpretation (`KeyBERT`)
4. ✅ Data visualization with Matplotlib

📦 Requirements
1. sentence-transformers
2. umap-learn
3. scikit-learn
4. matplotlib
5. keybert
6. wikipedia
7. numpy

🎯 Motivation

By combining sentence-level embeddings and topological structure, this project provides an intuitive map of how Wikipedia topics relate semantically. It demonstrates how modern NLP models can uncover rich latent structures in textual data.

🤝 Contributions

Contributions, issues, and improvements are welcome! Feel free to open a pull request or submit feedback.

