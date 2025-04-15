# agentic-RAG

📘 Overview

This project is an Agentic Retrieval-Augmented Generation (RAG) system built with Streamlit, powered by Google’s Gemini models, and optionally enhanced with real-time web search via Exa.

🔍 What It Does — In Plain English

It lets you upload PDFs or enter URLs, then chat with the content — like ChatGPT, but trained specifically on your files or webpages.

Here’s how it works:
	1.	📄 You upload a PDF or provide a URL
	2.	🧠 The content is split into chunks and embedded using Gemini’s embedding model
	3.	🗃️ Embeddings are stored in a Qdrant vector database for efficient retrieval
	4.	🤖 When you ask a question:
	•	The query is rewritten for clarity by a Gemini-powered agent
	•	The system retrieves relevant chunks from your documents (RAG)
	•	If nothing relevant is found, it can search the web using Exa
	•	The Gemini model then generates a precise response based on the retrieved context


🧠 Use Cases
	•	Ask complex questions about research papers or technical docs
	•	Summarize or analyze articles, blogs, or reports
	•	Use it as a personal research assistant or study tool
	•	Connect your private documents with live, web-based knowledge (when Exa is enabled)
