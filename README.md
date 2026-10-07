# Nafisa_Islam_Rifa
<!-- <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f2027,50:203a43,100:2c5364&text=Nafisa%20Islam%20Rifa&fontSize=38&fontAlignY=40" /> -->

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=NafisaIslamRifa&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>
# Nafisa Islam Rifa
MSc Data Science | AI Engineer | PhD Applicant

📍 United Kingdom  
📧 nafisaislamrifa@gmail.com  

---

## 🔬 Research Interests
- Multimodal Artificial Intelligence  
- Vision-Language Models  
- Medical Report Generation  
- Medical Image Analysis  
- Natural Language Processing  
- Machine Learning & Deep Learning  
- Explainable AI in Healthcare  
- Agentic AI, Retrieval-Augmented Generation (RAG) & LLM Evaluation  

---

## 🎓 Education

**University of Greenwich, United Kingdom**  
MSc in Data Science (Expected 2026)

**United International University, Bangladesh**  
BSc in Computer Science and Engineering  
Thesis: *Temporal Misalignment Tackling in Video Moment Retrieval*

---

## 📄 Publication

**Multimodal Emotion Recognition Using Visual and Thermal Image Fusion**  
IEEE ICCIT 2024  
URL:https://ieeexplore.ieee.org/document/11022356



**Visual Grounding and Explainability for Prompt-Driven Radiology Report Generation**  
MICAD 2026  
Accepted for publication and presentation  
URL: https://drive.google.com/file/d/1IQNNWdiXM0mmZVe9uwBSnbmuaUKDNe4s/view  

**Video Moment Retrieval: A Survey of Methods, Benchmarks, and Open Challenges in the Multimodal LLM Era**  
Computer Vision and Image Understanding (Elsevier)  
Under Review  
URL: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7442027

---

## 💻 Projects

### 🏠 UKNest: Agentic RAG Assistant for UK Newcomers (2026)
🔗 https://github.com/NafisaIslamRifa/uk-newcomer-assistant  

An AI assistant for people who have recently moved to the UK. It answers questions on right to work, eVisas and share codes, renting and deposits, council tax and NHS access, **using only official GOV.UK guidance**, and cites the page and last-updated date in every answer.

**Key Features**
- RAG over 15 GOV.UK guides with section-aware chunking, BGE embeddings and a **Qdrant** vector database
- **Model Context Protocol (MCP)** tool server with GOV.UK search, postcode lookup (postcodes.io) and nearby services (OpenStreetMap)
- LLM agent that chooses and combines tools, with **guardrails in code**: cited links are checked against tool results, and personal visa questions get general guidance plus an adviser referral rather than a yes/no
- Provider-agnostic LLM layer (OpenAI-compatible, Anthropic, Gemini); the live demo runs gpt-oss-120b on Groq
- Evaluation: Recall@5 and MRR of 1.00 on direct questions; tool-selection and citation accuracy of 1.00 in end-to-end agent tests
- Docker Compose deployment, GitHub Actions CI with offline unit tests, public Streamlit demo

**Tech Stack**  
Python • MCP • Qdrant • fastembed • Groq / OpenAI-compatible LLMs • Streamlit • Docker • GitHub Actions  

---

### 🚇 Agentic RAG-Powered London Tube Assistant (2026)
🔗 https://github.com/NafisaIslamRifa/london-tube-assistant 
🎥 Demo: https://london-tube-assistant.streamlit.app/  

An intelligent London Tube assistant that combines RAG over official TfL documents, agentic routing and live Transport for London APIs to answer both static and real-time travel questions.

**Key Features**
- Semantic retrieval with sentence-transformer embeddings, **ChromaDB** and cross-encoder reranking
- Local **Llama 3.2** (Ollama) for grounded answers
- Agentic routing between RAG, live TfL APIs (line status, fares, arrivals) and Tube map retrieval
- Interactive Streamlit app

**Tech Stack**  
Python • LangChain • ChromaDB • Sentence-Transformers • Ollama • TfL Unified API • Streamlit  

---

### 🧠 Build Large Language Model from Scratch (2025)
- Developed a GPT-like Large Language Model (LLM) from scratch to understand core transformer components.
- Implemented key modules including tokenization, embeddings, positional encoding, and multi-head self-attention.
- Followed and extended concepts from the book *"Build a Large Language Model (From Scratch)"* by Sebastian Raschka.
- Built end-to-end training and inference pipeline to explore how modern LLMs function internally.

---

### 🖼️ Build Multimodal Vision-Language Model from Scratch (2025)
- Implemented a multimodal Vision-Language Model (VLM) inspired by PaliGemma architecture.
- Integrated a **SigLIP Vision Transformer encoder** with **GemmaForCausalLM** for image-text understanding.
- Designed a custom `PaliGemmaForConditionalGeneration` model with a projection layer to align visual and textual embeddings.
- Focused on cross-modal representation learning and efficient visual-to-text generation.

---

### Electricity Demand Prediction in Bangladesh
- Time series forecasting using historical electricity demand data  
- Built dataset from PGCB sources  

---

### 📚 BookBridge  
🔗 https://github.com/NafisaIslamRifa/BookBridge  

A community-driven platform designed to connect book donors with readers and promote accessible knowledge sharing. The system allows users to browse available books, request donations, and manage listings efficiently.  

**Key Features**
- Book donation and request system  
- User-friendly browsing interface  
- Book listing and management  
- Search and filtering functionality  
- Promotes knowledge sharing and community engagement  

**Tech Stack**  
Python • Web Development • Database • UI Design  

---

### 👵 Elderly Care and Support  
🔗 https://github.com/NafisaIslamRifa/Elderly-Care-and-Support  

A support-oriented application aimed at assisting elderly individuals with daily needs, safety, and communication. The system focuses on improving accessibility and providing digital assistance for senior citizens.  

**Key Features**
- Emergency support and contact system  
- Daily assistance management  
- Elder-friendly interface design  
- Health and safety focused features  
- Caregiver communication support  

**Tech Stack**  
Python • Machine Learning • Web Development • Database  

## 🛠 Technical Skills

**Programming:** Python, SQL, PHP, JavaScript  
**Machine Learning:** PyTorch, TensorFlow, Scikit-learn, Deep Learning, Data Mining  
**Generative AI & LLMs:** RAG, Agentic AI, MCP, LangChain, LangGraph, Hugging Face Transformers, LoRA/QLoRA  
**Retrieval:** Embeddings, Vector Search, Reranking, Qdrant, ChromaDB  
**Data Science:** Data Analysis, Data Visualization  
**Database:** MySQL  
**Engineering:** Docker, GitHub Actions (CI), Streamlit, Git, Web Development  

---

## 🏆 Awards
Best Technical Presentation Award — IEEE ICCIT 2024  

---

## 🧑‍🔬 Services

- **Reviewer**, MI4MedFM Workshop at MICCAI 2026
- **Reviewer**, Women in Machine Learning (WiML) Workshop @ NeurIPS 2026

## 🔗 Connect With Me
Google Scholar: https://scholar.google.co.uk/citations?user=WGKC7egAAAAJ  
GitHub: https://github.com/NafisaIslamRifa  
LinkedIn: https://www.linkedin.com/in/nafisa-islam-rifa-71212b246/  

---
