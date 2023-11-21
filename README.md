# Unstructured-PDF-RAG-with-Langchain

Unstructured

-Utilize the Unstructured package for OCR, separating text and tables, and convert tables into HTML format.

Langchain

-Employ Chroma DB with Hugging Face's pre-trained models to establish a vector database for use as a retriever or storage for historical messages.

-Utilize MultiQueryRetriever, MultiQueryRetriever, and ContextualCompressionRetriever as methods for document retrieval.

-Use the load_qa_chain function in conjunction with the "refine" method to summarize documents and historical conversations.
