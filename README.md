# NatLangProcessing
This repository contains Natural Language Processing Projects.
The notebook contains the code for a end to end RAG system that queries Google API search engine to get relevant results of an input query. These top 10 search results are then 
preprocessed into chunks and their embeddings are stored in FAISS vector database. A out-of-box BART model is trained on the MS Marco dataset to answer short questions and then this trained model is used to generate responses using google search results as context. This pipeline allows real time question answering by leveraging Google API search results, RAG and model training. The following major steps are involved in the construction of this entire pipeline:

