<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=2EA8F5&center=true&vCenter=true&width=650&lines=Hi+there%2C+I'm+Yaseen+%F0%9F%91%8B;Final-Year+Civil+Engineer+%40+NIT+Trichy;Building+in+Data+Science+%26+Applied+ML;Agentic+Systems+%C2%B7+RAG+%C2%B7+Deep+Learning" alt="Typing SVG" />

[![GitHub followers](https://img.shields.io/github/followers/MohamedYaseenK?label=Follow&style=social)](https://github.com/MohamedYaseenK)
![Profile Views](https://komarev.com/ghpvc/?username=MohamedYaseenK&color=2EA8F5&style=flat)

</div>

---

### 👋 About Me

I'm a final-year **Civil Engineering** student at **NIT Tiruchirappalli**, transitioning into **Data Science & Machine Learning**. Over the past year I've gone from structural analysis to building agentic AI systems, RAG pipelines, and deep learning models — end to end, from data to deployment.

- 🎓 Final-year undergrad, NIT Trichy
- 🔁 Self-taught pivot into Data Science / ML / GenAI
- 🏭 Completed an internship at **BlueScope** (built an anomaly-detection Azure DevOps extension)
- 🎯 Currently building a portfolio around **agentic AI, RAG, and applied ML** for data science / analytics / product-fintech roles
- ⚡ Started coding in 11th standard — first project was a maze game in Scratch

---

### 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / Deep Learning**
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**LLMs / Agentic AI / RAG**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75FF?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

**Deployment / Tooling**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

---

### 🚀 Featured AI/ML Projects

#### 🕵️ [Agentic Fraud Detection System](https://github.com/MohamedYaseenK/agentic-fraud-detection)
An end-to-end fraud detection system on the PaySim dataset, combining a tuned **XGBoost** classifier with a **LangChain ReAct agent** (Gemini-backed) that investigates flagged transactions using three tools — user history, user profile, and automated case-report generation.
- Improved recall from **0.18% → 81.4% at 90% precision** — a **450x** lift over the dataset's naive rule baseline
- Engineered features including `dest_balance_untouched` to catch mule-account patterns
- Served via **FastAPI**, demoed on **Streamlit**, containerized with **Docker**, deployed on **Render**
- `XGBoost` `LangChain` `Gemini` `FastAPI` `Streamlit` `Docker`

#### 📖 [IS 456 RAG Assistant](https://github.com/MohamedYaseenK/is456-rag-assistant)
A retrieval-augmented QA system over **IS 456:2000**, India's 114-page OCR-scanned concrete design code — a genuinely messy real-world document (scanned tables, numeric lookups, inconsistent OCR).
- Built a quantitative **RAGAS** evaluation harness across 20 categorized test questions
- Diagnosed a context-recall gap (0.29) vs. high precision (0.88) on numeric/table lookups, and scoped a table-aware extraction fix
- Deployed as a rate-limited Streamlit app with automatic multi-provider LLM fallback for reliability
- `LangChain` `ChromaDB` `Sentence-Transformers` `Groq` `Gemini` `RAGAS`

#### 🎙️ [CPU-Only Streaming Voice Agent](https://github.com/MohamedYaseenK/streaming-voice-agent)
A real-time conversational voice agent running entirely on **CPU**, streaming audio over WebSockets through the full pipeline: turn-taking/VAD → STT → LLM → TTS → audio back to the client.
- Every pipeline stage instrumented and benchmarked — VAD, STT, LLM time-to-first-token, TTS, and total round-trip latency
- Deliverable-focused: a working round-trip demo plus a stage-by-stage latency breakdown
- `WebSockets` `VAD` `Speech-to-Text` `LLM` `Text-to-Speech`

#### 🏥 [Medical Chatbot RAG](https://github.com/MohamedYaseenK/medical-chatbot-rag)
A retrieval-augmented medical Q&A chatbot built on a **Flask** backend with **Pinecone** as the vector store.
- `LangChain` `Flask` `Pinecone` `Sentence-Transformers`

#### 🌊 Sea Surface Temperature Forecasting (Deep Learning)
A **ConvLSTM2D**-based spatiotemporal forecasting model on NOAA Reynolds OI SST data, focused on the Indian Ocean Dipole and Northern Indian Ocean region — built for my department and presented as a conference poster.
- Model evaluation via skill-score maps and Hovmöller diagrams for spatiotemporal validation
- `TensorFlow/Keras` `ConvLSTM2D` `NOAA Reynolds OI SST` `Geospatial Visualization`

#### 🔍 DevOps Audit Hub (BlueScope Internship)
An **Azure DevOps** marketplace extension for automated audit scoring with anomaly detection, built and shipped during my internship.
- Fixed scoring-formula vulnerabilities and PDF export issues; resolved VS Code Marketplace publishing pipeline issues
- `Azure DevOps Extensions` `Anomaly Detection`

---

### 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=MohamedYaseenK&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohamedYaseenK&layout=compact&hide_border=true" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=MohamedYaseenK&hide_border=true" />
</div>

---

### 🎯 Currently

- Sharpening SQL and ML fundamentals for data science interviews
- Preparing structured technical walkthroughs for the fraud-detection and RAG projects above
- Open to **Data Science / ML / Analytics** roles

---

<div align="center">

📫 Reach me on GitHub — <a href="https://github.com/MohamedYaseenK">@MohamedYaseenK</a>

</div>
