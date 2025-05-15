# ✨ RUBY – Travel Planning Chatbot

RUBY is an intelligent travel planning chatbot that leverages advanced Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG) to deliver a personalized, voice-enabled, and user-friendly travel planning experience.

---

## 🌍 Overview

RUBY helps users plan trips by generating customized itineraries, offering location-specific recommendations, and enabling real-time conversational interactions—all through a sleek web interface. It combines the power of LLaMA 3.0, sentence embeddings, and vector retrieval to understand user intent and provide meaningful responses.

---

## 🔑 Key Features

- 🗺️ **Personalized Itineraries**  
  Tailored travel plans based on user preferences, budget, and interests.

- 🗣️ **Voice Interaction**  
  Converts bot responses to speech using browser-based JavaScript APIs for an interactive experience.

- 🧠 **Contextual Understanding**  
  Utilizes sentence transformers and vector databases to retrieve the most relevant travel information.

- ⚡ **Fast & Scalable**  
  Built with modern tools to ensure quick responses and scalable performance.

---

## 🛠️ Tech Stack

### 💻 Frontend
- `HTML`, `CSS`, `JavaScript` – Responsive user interface with voice output via Web Speech API.

### 🧪 Backend
- `Flask` – Lightweight Python web server for handling routes and chatbot logic.
- `LangChain` – Framework for building context-aware, LLM-powered applications.

### 🧠 NLP Models
- `LLaMA 3.0` – Language model used for generating coherent and context-sensitive responses.
- `all-MiniLM-L6-v2` – Sentence Transformer for generating embeddings used in semantic search.

### 📦 Vector Storage
- `ChromaDB` – Vector database for efficient retrieval and RAG-based generation.

---

## 🚀 Getting Started

### 📥 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ruby-travel-chatbot.git
cd ruby-travel-chatbot

# Create virtual environment and activate it
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt
