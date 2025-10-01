# 🤖 RAG Pipeline & Chatbot  
*Automating Knowledge into Conversations with AI*  

<img width="1705" height="621" alt="RAG Pipeline   Chatbot image" src="https://github.com/user-attachments/assets/a27583c1-762a-4b0a-8089-6aaf3ad486e8" />

<!-- Replace with actual screenshot path -->

---

## 📌 Project Overview  
This project implements a **Retrieval-Augmented Generation (RAG) Pipeline** using **n8n**, **OpenAI**, and **Pinecone** to build a chatbot that can:  
- Ingest documents from Google Drive  
- Convert them into embeddings  
- Store them in a vector database (Pinecone)  
- Answer user queries with contextually accurate responses  

---

## 🎯 Problem Statement  
Businesses and teams often struggle with **scattered documentation**. Searching for answers manually is slow and inefficient.  
This project solves that by automating **document ingestion + retrieval + contextual answering** in real-time.

---

## ⚙️ Workflow Architecture  

**Steps:**  
1. **Trigger:** Google Drive upload event  
2. **Data Loader:** Extract file contents  
3. **Embedding:** Generate vector embeddings using OpenAI  
4. **Storage:** Store embeddings in Pinecone Vector DB  
5. **User Query:** Chat agent triggers OpenAI model  
6. **Context Retrieval:** Pinecone fetches relevant chunks  
7. **Response:** AI chatbot provides contextual answer  

**Tech Stack:**  
- [n8n](https://n8n.io/) (workflow automation)  
- [OpenAI API](https://platform.openai.com/) (embeddings + LLM)  
- [Pinecone](https://www.pinecone.io/) (vector database)  
- Google Drive API (document source)  

---

## 🖼️ Workflow Diagram  
<img width="512" height="193" alt="vector DB image" src="https://github.com/user-attachments/assets/da33a1be-8cb9-4b12-9810-ee750ed0a28f" />
<img width="512" height="316" alt="Workflow wireframe RAG" src="https://github.com/user-attachments/assets/2071c942-672a-4fb2-9423-29817da50270" />


---

## 🚀 Key Features  
- 📂 **Automated Document Ingestion** from Google Drive  
- 🔎 **Semantic Search** powered by Pinecone  
- 🧠 **Contextual Q&A** via OpenAI Chat Model  
- ⚡ **Low-latency responses** for real-time interactions  
- 🔄 **Scalable & modular workflow** built on n8n  

---

## 💡 Business Impact  
- ⏱️ **80% faster knowledge retrieval** compared to manual search  
- 📉 Reduced dependency on manual FAQ maintenance  
- 🤝 Usable for customer support, internal knowledge bases, or research  


---

## 🔮 Future Enhancements  
- Multi-source ingestion (Notion, Slack, Confluence)  
- Fine-tuned models for domain-specific Q&A  
- Frontend chatbot widget integration  
- Response caching for efficiency  

---

##  Author  
**Muskkan Iyer**  
AI Product Analyst | Data Enthusiast | Automation Builder  

- 🌐 [Portfolio](https://github.com/Muskkaniyer)  
- 💼 [LinkedIn](https://www.linkedin.com/in/muskkaniyer/)  
- 📧 Contact: [Gmail](mailto:muskkaniyer@gmail.com)  

---

⭐ If you found this useful, consider giving the repo a star!
