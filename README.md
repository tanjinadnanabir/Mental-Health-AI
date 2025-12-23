# 🧠 Mental Health AI Agent  
**An Empathetic, Intelligent, and Privacy-First Mental Health Support System**

> ⚠️ **Disclaimer**: This project is **not a replacement for professional mental health care**. It is designed to provide emotional support, mental health awareness, and crisis-aware guidance only.

---

## 🌟 Overview

The **Mental Health AI Agent** is an open-source, LLM-powered conversational system designed to provide **empathetic support**, **emotion recognition**, and **crisis-aware responses** using modern AI techniques such as **Retrieval-Augmented Generation (RAG)** and **Vector Databases**.

The agent is capable of understanding emotional context, detecting mental health risks, retrieving relevant coping strategies, and routing conversations to specialized sub-agents when required.

This project aims to serve as a **research-grade MVP** that can be deployed using **free and open-source resources**.

---

## 🚀 Project Proposal
  - https://docs.google.com/document/d/1ymitrjJulfX0mm4ukfDilsCps5i-PgpT/edit

## 🚀 Key Features

### 🧩 Core Capabilities
- **Emotion Recognition**
  - Detects emotions (e.g., anxiety, sadness, anger, fear, hopelessness, etc.)
  - Uses transformer-based emotion classification models

- **Empathetic & Supportive Conversations**
  - LLM-based response generation
  - Emotion-aware prompt engineering
  - Non-judgmental and human-centered dialogue

- **Crisis Detection & Safety Layer**
  - Identifies high-risk mental states (e.g., self-harm, suicidal ideation, etc.)
  - Provides immediate crisis resources and emergency guidance
  - Safe-completion and escalation rules

- **Memory & Personalization System**
  - Short-term and long-term memory via vector embeddings
  - Remembers user preferences, past emotional patterns, and coping strategies

- **Retrieval-Augmented Generation (RAG)**
  - Retrieves evidence-based mental health content
  - Uses **Milvus Vector Database**
  - Ensures grounded and contextually relevant responses

- **Intelligent Agent Routing**
  - Routes conversations to specialized agents:
    - Anxiety Support Agent
    - Depression Support Agent
    - Stress & Burnout Agent
    - Crisis Response Agent

---

## 🏗️ System Architecture

<img width="271" height="430" alt="image" src="https://github.com/user-attachments/assets/18851154-43d7-43a4-abac-ab5795f2bbe1" />

---

## 🛠️ Tech Stack

### AI & NLP
- Hugging Face Transformers
- Sentence Transformers
- Large Language Models (Open-Source / API-based)
- Prompt Engineering

### Vector Database
- **Milvus**
- FAISS (local alternative)

### Backend & Tools
- Python
- LangChain
- Jupyter Notebook / Google Colab
- Pandas & NumPy

### Deployment 
- Hugging Face Spaces
- Docker
- FastAPI / Streamlit

---

## 📚 Datasets (Optional)

- **EmpatheticDialogues**
- **GoEmotions**
- **Mental Health Reddit Dataset**
- **Custom Crisis & Therapy-Style Conversations**
- **Synthetic Emotion-Annotated Dialogues**

> All datasets will be used for **research and educational purposes only**.

---

## 🧪 Notebooks & Modules (development - on-going)

| Module | Description |
|------|------------|
| `emotion_detection.ipynb` | Emotion classification pipeline |
| `crisis_detection.ipynb` | Risk & crisis detection logic |
| `rag_pipeline.ipynb` | RAG with Milvus |
| `agent_router.ipynb` | Multi-agent routing |
| `chat_interface.ipynb` | End-to-end chatbot flow |

---

## ⚙️ Installation

```bash
git clone https://github.com/tanjinadnanabir/mental-health-ai.git
cd mental-health-ai
pip install -r requirements.txt
Milvus (Docker)
bash
Copy code
docker-compose up -d
▶️ Usage
Run the main notebook:

bash
Copy code
jupyter notebook main_agent.ipynb
Or deploy via API / UI (optional).

🔐 Ethics, Safety & Privacy
No personal data storage without consent
No diagnosis or medical advice
Crisis scenarios always trigger:
Emergency disclaimers
Local & global helpline suggestions
Designed with AI safety and human well-being in mind

🧩 Future Enhancements
Voice-based emotion recognition
Multilingual support (including Bengali 🇧🇩)
Therapist-in-the-loop feedback
Reinforcement Learning with Human Feedback (RLHF)
Wearable & EEG data integration (research)

🤝 Contributions
Contributions are welcome!
Feature requests
Dataset improvements
Model optimization
UI/UX enhancements
Ethical review & safety improvements

Please open an issue or submit a pull request.

📜 License
This project is licensed under the MIT License.

📬 Contact
Author: Tanjin Adnan Abir
Focus Areas: AI, NLP, Mental Health, RAG, Vector Databases
GitHub: https://github.com/tanjinadnanabir

Email: tanjinadnanabir@gmail.com

🌱 Final Note
“AI should not replace human care—but it can help people feel less alone.”
