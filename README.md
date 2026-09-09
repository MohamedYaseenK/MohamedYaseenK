<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=2EA8F5&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Yaseen+%F0%9F%91%8B;Civil+Engineer+by+degree%2C+ML+builder+by+choice;Agentic+Systems+%C2%B7+RAG+%C2%B7+Deep+Learning" alt="Typing SVG" />

[![GitHub followers](https://img.shields.io/github/followers/MohamedYaseenK?label=Follow&style=social)](https://github.com/MohamedYaseenK)
![Profile Views](https://komarev.com/ghpvc/?username=MohamedYaseenK&color=2EA8F5&style=flat)

</div>

<br>

## About

Two years ago I was studying moment distribution and reinforced concrete design. Today I build agentic AI systems that investigate financial fraud and RAG pipelines that parse dense, OCR-scanned engineering codes — the pivot was steeper than I expected, but the instinct for breaking a hard problem into a structured one carried over.

I'm a final-year **Civil Engineering** student at **NIT Tiruchirappalli**, self-taught in Data Science and ML, and I use a **BlueScope** internship as proof I can ship things that run in production, not just notebooks that run once.

- 🎓 Final-year undergrad, NIT Trichy — self-taught pivot into Data Science / ML / GenAI
- 🏭 BlueScope internship — built and shipped an Azure DevOps extension for anomaly detection, validated against live org data (110 contributors, 966 commits in a month)
- 🎯 Building a focused portfolio around **agentic AI, RAG, and applied ML**, aimed at Data Science / Analytics / Product-Fintech roles
- ⚡ Wrote my first program in 11th standard — a maze game in Scratch
- 🏆 Once walked into an unplanned structural engineering quiz at CSIR-SERC's diamond jubilee and won it, against seniors

---

## Stack

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
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

---

## Projects

### 🕵️ [Agentic Fraud Detection System](https://github.com/MohamedYaseenK/agentic-fraud-detection)
The one I'm proudest of. A tuned **XGBoost** classifier flags suspicious transactions on the PaySim dataset; a **LangChain ReAct agent** (Gemini-backed) then investigates each flag on its own — pulling user history, checking the account profile, and writing up a case report, in that order, without being told to at every step.

- Took recall from **0.18% to 81.4% at 90% precision** — a **450x** lift over the dataset's naive rule baseline
- `dest_balance_untouched`, an engineered feature that catches mule-account patterns rules miss
- Shipped end to end: **FastAPI** backend, **Streamlit** demo, **Dockerized**, live on **Streamlit Community Cloud**

### 📖 [IS 456 RAG Assistant](https://github.com/MohamedYaseenK/is456-rag-assistant)
A retrieval-augmented QA system over **IS 456:2000**, India's concrete design code — 114 pages, OCR-scanned, full of the scanned tables and numeric lookups that make real-world RAG hard.

- Built a quantitative **RAGAS** evaluation harness across 20 categorized test questions, instead of eyeballing outputs
- Found the actual weak spot: precision of 0.88, but context recall of only 0.29 on numeric/table lookups — and scoped a table-aware extraction fix for it
- Runs as a rate-limited Streamlit app with automatic multi-provider LLM fallback

### 🎙️ [CPU-Only Streaming Voice Agent](https://github.com/MohamedYaseenK/streaming-voice-agent)
A full conversational voice pipeline — WebSocket audio in, turn-taking detection, STT, LLM, TTS, audio streamed back out — running entirely on **CPU**, no GPU shortcuts.

- Every stage instrumented and benchmarked: VAD, STT, LLM time-to-first-token, TTS, total round-trip
- Built to answer one question precisely: where does the latency actually go?

### 🌊 [Sea Surface Temperature Forecasting](https://github.com/MohamedYaseenK/Analysis-and-Forecasting-of-monthly-Sea-Surface-Temperature-for-Indian-Ocean-Dipole-region.git)
A **ConvLSTM2D** spatiotemporal forecasting model on NOAA Reynolds OI SST data, focused on the Indian Ocean Dipole and Northern Indian Ocean. Built for my department, evaluated with skill-score maps and Hovmöller diagrams, and presented as a conference poster.

### 🔍 [DevOps Audit Hub — BlueScope Internship](https://github.com/MohamedYaseenK/Azure-DevOps-Extension-DevOps-Audit-Hub.git)
An **Azure DevOps** marketplace extension I built solo for developer productivity monitoring and anomaly detection — three layers: data retrieval (ADO REST + WIQL), identity normalization across sources, and rule-based anomaly detection behind a two-tier UI.

- Validated against live org data
- Debugged real production issues along the way: WIQL rejecting datetime comparisons, CORS errors from hand-rolled requests, and a silent access-level data restriction that was quietly cutting off results

### 🧪 [Bayesian A/B Test Analyzer *(in progress)*](https://github.com/MohamedYaseenK/Bayesian-AB-Tester-Analyzer.git)
A small MVP for analyzing A/B tests the Bayesian way, instead of squinting at p-values. Built on the MeuTutor gamified peer-assessment dataset (Tenório et al. 2017, *Data in Brief*), specifically the control-vs-gamification arm of Experiment 2.

- **FastAPI** backend, **Streamlit** dashboard, **Dockerized** — reusing the deployment pattern from the fraud detection project above

---

## Right now

- Sharpening SQL and ML fundamentals for data science interviews
- Building out structured technical walkthroughs for the fraud-detection and RAG projects above
- Open to **Data Science / ML / Analytics** roles

---

<div align="center">

📫 **[Connect on LinkedIn →](https://www.linkedin.com/in/mohamedyaseenk/)**

</div>
