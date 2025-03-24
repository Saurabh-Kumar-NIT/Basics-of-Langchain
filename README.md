📖 LangChain Basics - Learning Summary
✨ Overview
This repository contains my practical learning notes and implementation exercises while exploring the basics of LangChain.
It covers different data ingestion techniques, document chunking, embedding generation, and vector storage concepts.

🚀 Topics Covered
1️⃣ Data Ingestion Techniques
Explored how to load data from various sources:
Plain Text Files
PDF Documents
Web Pages
APIs
Databases
Tools Used: LangChain Loaders

2️⃣ Document Chunking
Handled large documents by splitting them into smaller, manageable chunks using:
RecursiveCharacterTextSplitter
Other splitters (depending on data type)
👉 Why: Improves retrieval accuracy and maintains context in large documents.

3️⃣ Embeddings Generation
Practiced creating embeddings to convert text chunks into numerical vectors using:
OpenAI Embeddings
Ollama Embeddings
Hugging Face Embeddings

4️⃣ Vector Store Databases
Learned how to store and retrieve embeddings efficiently using:
FAISS
AstraDB
(Also experimented with other LangChain-supported vector DBs)

🛠️ Tools & Libraries Used:
LangChain
FAISS
OpenAI API
Hugging Face Transformers
AstraDB
Python

📌 Key Takeaways:
Importance of splitting documents for better performance
Difference between embedding models
How vector stores power fast similarity search
Practical hands-on setup for document QnA systems

📂 Repository Purpose:
This is not a project, but a personal record of basic concepts + hands-on experiments I’ve done while learning LangChain fundamentals.

✅ Next Steps:
Explore LangChain Agents & Tools
Build end-to-end Document QnA application
Try chaining with LLMs for advanced workflows
