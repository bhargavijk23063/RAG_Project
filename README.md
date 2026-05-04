# RAG_Project
# 📌 RAG-Based Customer Support Assistant

## 🚀 Project Overview
This project implements a **Retrieval-Augmented Generation (RAG)** based Customer Support Assistant.

The system processes a PDF knowledge base and provides **accurate, context-aware answers** to user queries by retrieving relevant information.

It simulates a real-world customer support system with intelligent decision-making.

---

## 🎯 Objectives
- Process a PDF knowledge base
- Convert text into embeddings
- Store embeddings in ChromaDB
- Retrieve relevant information using semantic search
- Generate accurate answers
- Implement workflow-based processing (LangGraph concept)
- Support Human-in-the-Loop (HITL) escalation

---

## 🧠 Key Concepts
- Retrieval-Augmented Generation (RAG)
- Text Chunking
- Embeddings (Semantic Search)
- Vector Database (ChromaDB)
- Query Processing
- Conditional Routing
- Human-in-the-Loop (HITL)

---

## 🏗️ System Architecture
The system consists of:

- **PDF Loader** → Loads document  
- **Chunking Module** → Splits text  
- **Embedding Model** → Converts text into vectors  
- **Vector Database (ChromaDB)** → Stores embeddings  
- **Retriever** → Fetches relevant data  
- **Processing Layer** → Generates answer  
- **Routing Layer** → Decides output  
- **HITL Module** → Escalates complex queries  

---

## 🔄 Workflow
1. User enters query  
2. System retrieves relevant chunks  
3. Best matching answer is extracted  
4. If answer is weak → escalate to human  
5. Else → return response  

---

## ⚙️ Technologies Used
- Python  
- LangChain  
- ChromaDB  
- HuggingFace Embeddings  


---

## ▶️ How to Run
1. Install dependencies:
pip install langchain langchain-community chromadb transformers

2. Run:
python rag.py

3. Ask queries:
how long does refund take?

---

## 🧪 Sample Queries
- What is return policy?
- How long does refund take?
- What is delivery time?
- Can I cancel after 2 days?

---

## 🤝 Human-in-the-Loop (HITL)
If the system cannot confidently answer:
Escalating to human...

This ensures reliability in real-world scenarios.

---

## 🎥 Project Demo Video
[Click here to watch the demo](https://drive.google.com/file/d/1B28N1KoEbyFNWYAxwOQ9E8OqCRtdGYuS/view?usp=sharing)

---

## ⚖️ Challenges & Trade-offs
- Accuracy vs speed  
- Chunk size vs context quality  
- Lightweight models vs performance  

---

## 🔮 Future Enhancements
- Multi-document support  
- Web-based UI  
- Better LLM integration  
- Feedback learning system  
- Cloud deployment  

---

## 📌 Conclusion
This project demonstrates how RAG systems can be used to build scalable and intelligent customer support assistants with decision-making capability.

---

## 📎 Deliverables Included
- HLD Document (PDF)
- LLD Document (PDF)
- Technical Documentation (PDF)
- Working Project Code
