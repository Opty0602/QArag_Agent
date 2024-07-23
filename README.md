# qaRag_Agent

This is a python notebook file. The code works complety fine but needs to be optimized greatly.
It incorporates the ensembled retreival mechanism with BM25 and using FAISS vectorstore as retreival.

At the end there is a cell with simple gradio interface.Though we get the results out from the Agent but it apparently takes 5mins to generate output(which is way too much).
This could probably because of the low specs of my pc I devoloped the code in and high functioning requirements of the llm and embedding model used.

LLM Model used: GPT4ALL - mistral-7b-openorca.Q4_0.gguf (4.11GB)                      
Embedding Model Used: GPT4AllEmbeddings - all-MiniLM-L6-v2.gguf2.f16.gguf (<100MBs)

One could also find two docstore_index folder, semanticdocstore_index is vectorstore of chunks created by Semantic Chunking using aforementioned Embedding Model, whereas other vectorstore folder contains vectorestore embeddings by performing RecursiveTextSplitting.


Though I didnt have much experience with RAGs but even by doing this home assigment challenged my capabilities. I had fun doing it and do realise the places I lack behind.

And Thanks you Steps AI for showing interest and giving me a chance.
