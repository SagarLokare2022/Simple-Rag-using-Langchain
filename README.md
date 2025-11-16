YouTube Transcript RAG System Using Whisper + LangChain

This project demonstrates how to convert any public YouTube video into a searchable knowledge system using a Retrieval Augmented Generation (RAG) pipeline.
It uses Whisper (OpenAI) for transcription, LangChain for chunking + embedding, and FAISS for vector search.

🎯 Project Features

Extract transcript from any YouTube video (via audio download + Whisper)

Chunk long text using LangChain’s RecursiveCharacterTextSplitter

Convert chunks into embeddings

Store/retrieve chunks using FAISS vector store

Create a RAG chatbot that answers questions based on the video transcript

Build simple sequential and parallel LangChain pipelines

Includes sample output + visualization

📌 Tech Stack

Python 3.10+

Whisper (OpenAI API)

LangChain

FAISS

Pytubefix (to download YouTube audio)

Jupyter Notebook (.ipynb)

🚀 How It Works (High-Level)

Download YouTube audio

Use Whisper to convert audio → text

Clean & chunk transcript (2000 chars, 500 overlap suggested)

Embed the chunks

Store chunks in FAISS

Query using RAG pipeline

Final chain returns structured, clean answers

📂 Project Structure
│── Rag_chatbot.ipynb        # Full RAG notebook with code + outputs
│── audio.mp4                # Sample audio extracted from YouTube
│── README.md                # This documentation

🧠 Improvements Planned

Add Streamlit UI

Add option to choose models (Gemini, OpenAI, Llama3)

Support for multiple video inputs

Export transcripts and summaries as PDF

Build a full conversational chatbot

👤 Author

Sagar Lokare
Fractal Senior Consultant | Building end-to-end GenAI Solutions

⭐ Show Support

If you find this useful, please ⭐ the repo!
