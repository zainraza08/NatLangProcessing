# NatLangProcessing
This repository contains Natural Language Processing Projects.
The notebook NLP_Realtime_Google_RAG_pipeline contains the code for a end to end RAG pipeline that queries Google API search engine to get relevant results of an input query. These top 10 search results are then 
preprocessed into chunks and their embeddings are stored in FAISS vector database. A out-of-box BART model is trained on the MS Marco dataset to answer short questions and then this trained model is used to generate responses using google search results as context. This pipeline allows real time question answering by leveraging Google API search results, RAG and model training. The major components of the pipeline are presented in this image below
<img width="581" alt="image" src="https://github.com/user-attachments/assets/fd0c91c1-3493-4efc-9d04-460038b3c389" />


