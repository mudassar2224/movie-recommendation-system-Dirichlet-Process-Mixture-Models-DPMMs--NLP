🚀 Built an AI Movie Search & Recommendation System using NLP + Unsupervised Learning

I recently worked on a project where I built a semantic movie search engine that recommends movies based on meaning rather than keywords.

🔍 What I implemented:

• Text embedding using Sentence Transformers
→ Model: BAAI/bge-base-en-v1.5 from Hugging Face

• Dimensionality reduction using PCA

• Clustering using Dirichlet Process (Bayesian Gaussian Mixture)
→ Automatically discovers movie groups without predefined cluster count

• Similarity search using cosine similarity

• Interactive UI built with Gradio

• Movie metadata processed from dataset (overview, genres, keywords, cast, crew)

💡 How it works:

1. Convert movie descriptions into embeddings
2. Reduce dimensions using PCA
3. Cluster movies using DPMM
4. For a user query → encode → transform → find similar movies
5. Display results with posters and YouTube search links

📦 Model & Data Handling:

• Saved embeddings using NumPy
• Saved clustering model using Pickle
• Reloaded everything for fast inference



🧠 Key Learning:

This project helped me understand:
• Embedding-based search
• Unsupervised clustering (DPMM)
• Building end-to-end ML pipelines
• Deploying ML apps with Gradio
If you need project tell me 


#MachineLearning #NLP #UnsupervisedLearning #AI #Python #Gradio
