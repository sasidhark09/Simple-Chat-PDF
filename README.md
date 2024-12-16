This is a simple LLM application[application of RAG] developed using Langchain, Googlegenai, streamlit, FAISS vector database.
For efficient extraction and analysis of text from Uploaded pdf documents.

Retrieval Augmented Generation:
1. Load -> Loading Data from different datasources[pdf's, images, url's, json, text...]
2. Split -> Spliting of Data into Text Chunks
3. Embed -> Embedding text [Text to Vectors]
4. Store -> Storing Vectors in Database for easy retrieval[Based on similarity search].


Execution:

Multiple pdf's converted into single text corpus.

Corpus then splitted into data chunks with specified chunksize and chunk_overlap.

Applied a free model of GoogleGenerativeAI embeddings to convert data chunks into context rich vectors.

Used FAISS [Facebook AI similarity Search] database for storing the vectors.


![image](https://github.com/user-attachments/assets/16c7faa5-1e2a-4e72-9c5d-53c293786501)


















