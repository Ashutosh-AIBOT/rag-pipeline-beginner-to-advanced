# 🔭 AI Research Assistant — Multi-Source Topic Explorer

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red?style=flat-square&logo=streamlit)
![LangChain](https://img.shields.io/badge/Framework-LangChain-purple?style=flat-square)
![Status](https://img.shields.io/badge/Stage-Complete-green?style=flat-square)

---

👤 **Author:** [Ashutosh](https://github.com/Ashutosh-AIBOT) · [LinkedIn](https://www.linkedin.com/in/ashutosh1975271/)
💼 **Portfolio:** [ashutosh-portfolio-kappa.vercel.app](https://ashutosh-portfolio-kappa.vercel.app/)

---

## 🧠 What This Does

Ask any research topic → AI searches web, arxiv papers,
GitHub repos, and documents simultaneously → returns
cited, structured answers with source links.

---

## ✨ Features

| Feature | Detail |
|---------|--------|
| 🌐 Web Research | Live web search + summarization |
| 📚 Paper Search | arxiv research paper discovery |
| 🐙 GitHub Search | Find relevant repos and code |
| 📄 Doc Upload | Chat with your own documents |
| 📝 Cited Answers | Every answer includes sources |

---

## 🏗️ Architecture
```
User Query
        ↓
Source Selector
  ├── Web Search
  ├── arxiv Papers
  ├── GitHub Repos
  └── Uploaded Docs
        ↓
Parallel Retrieval
        ↓
LangChain Synthesis
  → Combine results
  → Generate cited answer
        ↓
Streamlit Display
  → Answer + source cards
```

---

## ⚡ Quick Start
```bash
git clone https://github.com/Ashutosh-AIBOT/ai-research-assistant-app.git
cd ai-research-assistant-app
pip install -r requirements.txt
cp .env.example .env
streamlit run app.py
```

---

## 🛠️ Tech Stack

`Python` `Streamlit` `LangChain` `FAISS` `arxiv API` `GitHub API` `OpenAI` `Git`

---

## 👤 Author
**Ashutosh** · B.Tech Electronics Engineering · Batch 2026
[GitHub](https://github.com/Ashutosh-AIBOT) · [LinkedIn](https://www.linkedin.com/in/ashutosh1975271/)

> *"Research in minutes. Not hours."*
```
