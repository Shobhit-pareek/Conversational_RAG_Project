# Conversational_RAG_Project
Conversational RAG with PDF Uploads and Chat History

This Streamlit application provides a Retrieval-Augmented Generation (RAG) chatbot that enables users to upload PDF documents and interact with their content through conversational Q&A. The chatbot maintains a chat history to provide context-aware responses and utilizes Groq API and LangChain framework for enhanced capabilities.

**Features**

**PDF Upload and Processing:**
Upload multiple PDF files.
Automatically extract and process text content for retrieval.

**Conversational Q&A:**
Context-aware responses based on user queries.
Maintains a chat history for better understanding of follow-up questions.

**History-Aware Question Reformulation:**
Reformulates user queries to be standalone and contextually complete using the chat history.

**Embeddings for Document Retrieval:**
Splits documents into manageable chunks.
Generates embeddings using Hugging Face models for efficient retrieval.

**Customizable Model and Tools:**
Powered by Groq API with Gemma2-9b-It for state-of-the-art responses.

**Workflow**

**Upload PDFs:**
Use the file uploader to add PDFs to the application.
The content is extracted and split into smaller chunks for better processing.

**Chat with PDFs:**
Enter a question in the text input field.
The app retrieves relevant document chunks and provides concise answers using the RAG pipeline.

**Chat History:**
Maintains session-based chat history for context-aware responses.
Reformulates user queries to make them independent of previous conversation context.

**Tools and Capabilities**

**Retrieval:**
Uses Chroma for document retrieval based on embeddings.

**Chat History:**
Built-in support for managing and utilizing chat history to refine responses.

**LLM Integration:**
Powered by Groq API's Gemma2-9b-It for generating responses.
