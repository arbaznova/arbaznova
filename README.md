## Hi, I'm Arbaz 👋

Backend Engineer focused on building **scalable systems** and **AI-powered applications**.

- 🔧 Working with **Go (Gin), Java, and Python**
- 🧠 Exploring **LLM-based systems, agents, and backend automation**
- ⚙️ Interested in **system design, concurrency, and real-time systems**
- 🚀 Currently building **MetaCopilot** — a conversational AI layer for OpenMetadata

---

### What I care about
I enjoy building systems that are:
- Scalable and production-oriented  
- Modular and easy to extend  
- Designed with real-world constraints in mind  

---

### Tech Stack
`Go` • `Java` • `Python` • `Gin` • `Spring Boot` • `PostgreSQL`  
`LangChain` • `LLMs` • `REST APIs` • `System Design`

---

### Currently
- Building AI-integrated backend systems  
- Learning more about distributed systems and scalable architectures  

---

📫 Reach me: **mohdarbazkhilji@gmail.com**  
🔗 LinkedIn: https://linkedin.com/in/mohammad-arbaz-khilji-5961852a3
---

## 🛠Featured Projects
# 1. MetaCopilot 🚀  
**Conversational AI for OpenMetadata**

MetaCopilot is a **multi-tenant SaaS platform** that lets you explore your OpenMetadata data catalog using **natural language**.

Instead of navigating multiple UI layers, just ask:
> “Show me tables related to orders”  
> “What columns exist in payments?”  
> “Give me lineage for this dataset”

---

## ✨ Features

- 🧠 **LLM-powered agent**  
  Uses Google Gemini (via LangChain) to interpret queries and fetch relevant metadata  

- 🔗 **Dynamic API routing**  
  Automatically selects the right OpenMetadata APIs (search, schema, lineage)

- 🏢 **Multi-tenant architecture**  
  Organization-level isolation with secure user management  

- 🔐 **Secure integration**  
  Connect your own OpenMetadata instance via JWT-based bot authentication  
  → No data is hosted, only API interaction  

- 💬 **Stateful chat interface**  
  Persistent chat history for contextual conversations  

---

## 🏗️ Tech Stack

- **Backend:** Go (Gin)  
- **Frontend:** React + Vite  
- **Database/Auth:** PostgreSQL + Supabase  
- **AI:** LangChain (Go) + Google Gemini 1.5 Pro  
- **Ecosystem:** OpenMetadata REST APIs  

---

## ⚙️ How it works

1. User asks a question in natural language  
2. LLM agent parses intent and context  
3. System maps query → appropriate OpenMetadata API  
4. Fetches and returns structured results  
5. Chat history maintains context across queries  

---

## 🚀 Getting Started

Detailed setup instructions are available in the repo.  
You can run MetaCopilot locally with your own OpenMetadata instance.

## 2. Secure Multithreaded Chat Server
**Technologies:** Java, TLS, X.509 PKI, TCP, Concurrency

**Description:**  
A production-oriented real-time chat server engineered from the ground up using core Java. Designed for high concurrency, secure messaging, and scalability without relying on external frameworks.

**Key Features:**
- Custom application-layer protocol with command-based routing
- TLS-secured communication using X.509 certificates
- Thread-pool–driven concurrency with backpressure handling
- Lock-free registries for user and session management
- Observability hooks for monitoring server health
- Chatbot-ready architecture for future AI integration

**Status:** ✅ Working

---

## 3. LLM-Powered Chatbot Service (Java–Python Integration)
**Technologies:** Python, FastAPI, LLM APIs, Java integration, TLS

**Description:**  
A Python-based chatbot service designed to integrate with my Java chat server. Enables conversational AI responses with session-aware context and a pluggable backend architecture.

**Key Features:**
- Secure, language-agnostic protocol bridge between Java server and Python service
- Session-aware conversation memory for multi-turn interactions
- Prompt orchestration and routing layers to control AI responses
- Low-latency design with future support for token-level streaming
- Backend-only exposure to ensure secure deployment
- Pluggable LLM integration to swap AI providers without affecting server

**Status:** ⚙️ In Progress

---

## 

📌 Interests: Backend Systems • Distributed Systems • Security • Web3 Infra • LLM Chatbots
📈 Building in public. Learning in depth.
