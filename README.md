# 🤖 MediChat-AI

**MediChat-AI** is an AI-powered **Medical Chatbot** that uses **Large Language Models (LLMs)** and **LangChain** to provide intelligent medical responses.  
It integrates with **Pinecone** for vector search, **Flask** for the backend API, and is deployable on **AWS** with a complete CI/CD pipeline using **GitHub Actions**.

---

## 🚀 Features

-  Conversational AI chatbot for healthcare-related queries  
-  Context-aware medical response generation using **LLMs + LangChain**  
-  Vector-based similarity search with **Pinecone**  
-  Flask-based backend server  
-  Fully deployable on **AWS** (ECR + EC2) via **GitHub Actions**  
-  Environment variables for secure API key handling  

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Flask |
| AI/LLM | LangChain, Google Generative AI (Gemini) |
| Vector Database | Pinecone |
| Deployment | AWS (ECR, EC2) |
| CI/CD | GitHub Actions |
| Environment | Conda |

---

## ⚙️ Setup Instructions

### 🏁 Step 1 — Clone the Repository

```bash
git clone https://github.com/<your-username>/MediChat-AI.git
cd MediChat-AI
