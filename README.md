# RAG-based-Chatbot
It is complete structue of RAG-based chatbot.
PDF is the Dataset used for creating vector embeddings.
Preprocessing performs OCR usign Cloud Vision and collects textual and other data from the PDF.
Three models are used to create vector embeddings (LaBSE, LASER, Langchain).
Results are uploaded in Pinecone.
Similarity search is performed based on topic related query, Gemini-1.5-flash is used as LLM.
