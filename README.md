# Budget-AI-Assistant: RAG with Falcon-7b
This project implements a Retrieval-Augmented Generation (RAG) system to query the 2026-2027 Union Budget of India speech.

## Features
Document Loading: Processes direct PDF links using PyPDFLoader.

Efficient Inference: Loads Falcon-7b in 4-bit precision to fit within 15GB VRAM limits.

Precise Retrieval: Uses Recursive Text Splitting to maintain context integrity.

## Tech Stack
Framework: LangChain

LLM: Falcon-7b (via Hugging Face)

Vector Store: ChromaDB

Quantization: BitsAndBytes (4-bit)

## How to Run
Clone the repo.

Install dependencies: pip install langchain-huggingface langchain-chroma transformers bitsandbytes pypdf.

Open the notebook in Google Colab and set Runtime to T4 GPU.

💡 Final Polish for Your Code
Before you push to GitHub, make sure your code is clean:

Remove any sensitive API keys (if you used any).

Add Comments: Ensure your typos (like pipline or promp) are fixed in the final version so other developers can follow it easily.

Add a Requirements.txt: This makes it easy for others to run your code with one command.
