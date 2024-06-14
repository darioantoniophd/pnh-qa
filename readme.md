# pnh-qa-langchain-chroma.ipynb
This is a simple Q&A application that provides information about Parque Nacional Nahuel Huapi.
It uses the LangChain library to generate answers based on a set of documents. Leverages a react agent.
The documents are stored in a persistent Chroma vector store
It uses OpenAI embeddings and OpenAI gpt-3.5-turbo model.

# pnh-rag.llamaparse-createpinecone.ipynb
This is a simple Q&A application that provides information about Parque Nacional Nahuel Huapi.
It uses the LlamaParse library to parse the documents. OpenAI to generate embeddings and gpt-3.5-turbo as language model. LlamaIndex to retrieve documents.
It uses Pinecone vector store to store the embeddings.

# pnh-rag.llamaparse-existingpinecone.ipynb
Same as previous but from an existing pinecone index.

# The data docs are not uploaded to github

# Integrating LlamaIndex with Pinecone docs

https://docs.llamaindex.ai/en/latest/examples/vector_stores/PineconeIndexDemo/

https://docs.pinecone.io/integrations/llamaindex