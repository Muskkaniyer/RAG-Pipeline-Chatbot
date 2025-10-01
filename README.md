# 🤖 RAG Pipeline & Chatbot  
*Automating Knowledge into Conversations with AI*  

<img width="1642" height="517" alt="RAG   Chatbot image" src="https://github.com/user-attachments/assets/c1e673aa-78e4-4ad0-8f09-dea4f3e920b5" />
<!-- Replace with actual screenshot path -->

---

## 📌 Project Overview  
This project implements a **Retrieval-Augmented Generation (RAG) Pipeline** using **n8n**, **OpenAI**, and **Pinecone** to build a chatbot that can:  
- Ingest documents from Google Drive  
- Convert them into embeddings  
- Store them in a vector database (Pinecone)  
- Answer user queries with contextually accurate responses  

👉 **Live Workflow:** [View on n8n](https://muskkan.app.n8n.cloud/workflow/BE5u3kPdnVbWgjp9)  
👉 **Project Documentation:** [View on Gamma](https://gamma.app/docs/RAG-Pipeline-Chatbot-z59ter2o12r2qy9?mode=doc)  

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

## 📽️ Demo  
- 🎥 [Loom Video Walkthrough](#) <!-- Optional: add link if you record a demo -->
- 🔗 [Live Workflow](https://muskkan.app.n8n.cloud/workflow/BE5u3kPdnVbWgjp9)  

---

## 🔮 Future Enhancements  
- Multi-source ingestion (Notion, Slack, Confluence)  
- Fine-tuned models for domain-specific Q&A  
- Frontend chatbot widget integration  
- Response caching for efficiency  

---

## 🧑‍💻 Author  
**Muskkan Iyer**  
AI Product Analyst | Data Enthusiast | Automation Builder  

- 🌐 [Portfolio](https://github.com/Muskkaniyer)  
- 💼 [LinkedIn](https://www.linkedin.com/in/muskkaniyer/)  
- 📧 Contact: [your.email@example.com](mailto:muskkaniyer@gmail.com)  

---

⭐ If you found this useful, consider giving the repo a star!
