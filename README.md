<h1 align="center">Hi 👋, I'm Monish Singal</h1>
<h3 align="center">AI/ML Engineer • Agentic systems, RAG & LLM pipelines — built to be reliable</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Monish-3d&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

## 🚀 About Me

- 🎓 B.Tech IT @ **IIIT Una** (CGPA 8.12) — into LLMs, system design & scalable AI systems
- 🤖 I build **agentic AI**: LangGraph state machines, self-corrective RAG, and LLM-guided pipelines — with a hard focus on **reliability** (validation gates, grounding checks, honest "I don't know" paths)
- 🛠️ Comfortable end-to-end: **FastAPI** backends, **classical ML** (scikit-learn / XGBoost / LightGBM), and production-shaped retrieval
- 🧩 **600+** LeetCode problems solved · CodeChef **2★** (1423)
- 🎮 Started out in **Unity (C#)** game dev — now deep in LLMs & AI systems

---

## 🧠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2A6FDB?style=flat&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8E44AD?style=flat&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Agentic AI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=flat&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

**Backend & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

---

## 🔨 Featured Projects

### 🤖 [AgentML](https://github.com/Monish-3d/AgentML) — Agentic AutoML Preprocessing Pipeline
A **10-node LangGraph** pipeline that turns a raw CSV/Excel into a clean, ML-ready dataset — schema detection, full EDA, an LLM-proposed preprocessing plan, and leakage-aware execution. The LLM only proposes *intent*; deterministic code decides *how*, *whether*, and *in what order*. A **Pydantic validation node** cross-checks every step against the real DataFrame, so **0 hallucinated steps reach execution** across 42 LLM steps on 9 datasets (1K–300K rows). Served over **FastAPI** with background jobs + node-level progress streaming (~9.3s end-to-end up to 20K rows).

`LangGraph` · `FastAPI` · `Pydantic` · `LangSmith` · `scikit-learn` · `imbalanced-learn`

### 📈 [Customer Lifetime Value Prediction](https://github.com/Monish-3d/Customer-Lifetime-Value-Prediction) — 90-Day Spend Forecasting
<!-- TODO: verify this repo URL -->
Forecasts each customer's next-90-day spend on **UCI Online Retail II** (1M+ transactions). The real challenge is a **leakage-free target**: a single cutoff date splits past (features) from future (target), *proven* with a **13-check mutation-test audit** that corrupts future data and confirms all 11 RFM features stay bit-identical. An Optuna-tuned **Random Forest** reaches **test MAE £332 (27% below baseline)**, and ranking by predicted value puts **54% of revenue in the top decile (5.4× lift)**. Drivers interpreted with **SHAP**.

`scikit-learn` · `XGBoost` · `LightGBM` · `Optuna` · `SHAP`

### 🔎 [Self-Corrective RAG Assistant](https://github.com/Monish-3d/express-analytics-rag-assistant) — RAG That Won't Hallucinate
An agentic RAG assistant over technical docs that **grades its own retrievals**. A **LangGraph** state machine routes on the grade: answer with citations, rewrite-and-retry, fall back to web search, or honestly say *"I don't know."* A **Self-RAG grounding check** audits every answer against its sources before returning it, and each response ships a full decision trace so the behaviour is auditable. **FastAPI** + **ChromaDB** + Tavily, with **68 tests** that run fully offline via dependency injection.

`LangGraph` · `FastAPI` · `ChromaDB` · `OpenAI` · `Tavily` · `pytest`

### 📝 [Marks-Grader](https://github.com/Monish-3d/Marks-Grader) — Hybrid-RAG Grading Engine
<!-- TODO: verify this repo URL -->
Grades handwritten answer sheets against **textbook evidence**. Fuses **Pinecone** dense search with **BM25** lexical search, de-duped to the top-3 grounding passages, then scores with a multi-signal ensemble (**0.6** LLM rubric / **0.2** cosine / **0.2** keyword) to cut single-model variance. Uses a **multimodal LLM** to do OCR + question segmentation in one call, and ships a difficulty-controlled **MCQ generator** via Pydantic structured output.

`LangChain (LCEL)` · `Pinecone` · `BM25` · `Gemini 2.5 Flash` · `HuggingFace` · `Streamlit`

<sub>🎮 Earlier work — <b>Odyssey to the Lost Relics</b> (2D Unity platformer) · <b>Turbo Tracks</b> (kart racer), in C# / Unity.</sub>

---

## 🏆 Achievements

- 🥉 **3rd place**, Advitiya Game Jam (team) — IIT Ropar, 2025
- 🎯 **ATF Fellowship** Stage-2 candidate — top **13%**, AlgoUniversity 2024
- 📚 **97.4 percentile** JEE Mains 2023 · **96.6%** CBSE Grade 12 (**District Rank 1**)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Monish-3d&show_icons=true&count_private=true&hide_border=true" alt="Monish's GitHub stats" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Monish-3d&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Monish-3d&layout=compact&hide_border=true" alt="Top languages" />
</p>

---

## 🤝 Connect

<p>
  <a href="https://www.linkedin.com/in/monish05/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:monishsingal05@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
</p>
