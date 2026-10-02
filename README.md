<div align="center">

# 🧠 Enterprise Knowledge Copilot
### *Next-Gen RAG-Based AI Assistant & Intelligent Context Engine*

<br>

[![Live Demo](https://img.shields.io/badge/🚀_Explore_Live_App-copilot--xi--lyart.vercel.app-blueviolet?style=for-the-badge)](https://copilot-xi-lyart.vercel.app)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)]()
[![LangChain](https://img.shields.io/badge/AI-LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)]()
[![ChromaDB](https://img.shields.io/badge/VectorDB-ChromaDB-orange?style=for-the-badge)]()

</div>

---

## ⚡ System Architecture & Overview
**Enterprise Knowledge Copilot** ek production-ready Retrieval-Augmented Generation (RAG) system hai, jo internal PDFs ko ingest karke secure aur context-aware querying perform karta hai[cite: 9]. Isme role-based access control (Admin/Viewer) ka support diya gaya hai[cite: 9], jo cloud deployment par maximum stability ensure karta hai[cite: 9].

---

## 🛠️ Core Engineering Highlights

*   📄 **Advanced Ingestion Pipeline:** Custom implementation of PDF parsing, smart chunking, and high-precision Gemini embeddings[cite: 9].
*   🗄️ **Optimized Vector Management:** Utilized `chromadb.EphemeralClient` locally to bypass strict cloud storage limits and guarantee stable Render deployments[cite: 9].
*   🔒 **Secure RBAC Security:** Strict role-based routing and authorization mechanisms for enterprise-grade data protection[cite: 9].
*   ⚡ **High-Speed Workflow:** Seamless full-stack integration built to handle intensive query loads with lightning-fast response times.

---

## 📊 Tech Stack Breakdown

| Layer / Domain | Technologies & Tools |
| :--- | :--- |
| **AI & Orchestration** | LangChain, Google Gemini API, Embeddings[cite: 9] |
| **Backend Core** | FastAPI, Python, JWT Authentication[cite: 9] |
| **Vector Database** | ChromaDB (In-Memory / Ephemeral Client)[cite: 9] |
| **Frontend / UI** | Next.js, Modern CSS Components[cite: 9] |
| **Cloud & Deployment** | Vercel (Frontend), Render (Backend)[cite: 9] |

---

## 🚀 Quick Setup & Installation

Apne local machine par isko run karne ke liye ye steps follow karein:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/shubham197369/enterprise-copilot.git](https://github.com/shubham197369/enterprise-copilot.git)
