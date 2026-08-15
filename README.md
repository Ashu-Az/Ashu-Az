# 👋 Hi, I'm Ashu Azad

**AI/ML engineer & independent researcher** — RL for LLM alignment · LLM training dynamics · mechanistic interpretability

My thing: **implementing research papers from scratch and checking whether their claims survive replication.**

🌐 **[Explore my portfolio →](https://portfolio-ivory-omega-17.vercel.app)** — a hacker-terminal site with an interactive shell (`Cmd+K`), live per-project visualisations, and **superashu**, my own AI chatbot. &nbsp;·&nbsp; [source](https://github.com/Ashu-Az/portfolio-site)

## 🔬 Research

- 🧪 **[s-sppo](https://github.com/Ashu-Az/s-sppo)** — **First public implementation of S-SPPO (ICML 2026)**, an RL self-play alignment method, plus the vanilla SPPO baseline and both ablations. Ran a full replication study on a 16GB laptop: confirmed the paper's judge-miscalibration premise, showed semantic gating prevents late-iteration decay — and found the paper's second component is a **no-op at its stated hyperparameters** (checkpoints come out bit-identical, 3×10⁻⁸ weight diff). Nobody could verify this before: the authors never released their code.

- 🔍 **[induction-heads](https://github.com/Ashu-Az/induction-heads)** — Trained a 2-layer transformer from scratch and **reverse-engineered the circuit that forms inside it**: previous-token head (0.92 sub-diagonal attention), copy-machine OV circuit (28× diagonal dominance), and a causal ablation that collapses P(B) from 0.67 → 0.06. Bonus war story: my first version hit 100% accuracy with **zero real induction** — a positional shortcut only mechanistic analysis could catch.

## 🚀 Production AI (work highlights)

- 🏭 **Enterprise RAG systems** — Azure OpenAI + FAISS pipeline over 1,000+ PDFs: hybrid retrieval (dense + BM25), cross-encoder reranking, semantic chunking — response time 30s → 2s, hallucinations −60%.
- ⚡ **ML systems engineering** — microservices serving 10,000+ users (API latency 400ms → <150ms), Redis-cached inference pipelines eliminating 60% of database queries.

## 🛠️ Systems I've built

- 🚗 **[Self_Driving_Car](https://github.com/Ashu-Az/Self_Driving_Car)** — end-to-end CNN (NVIDIA PilotNet-style) steering a simulated car **in real time** from raw camera frames.
- 🔎 **[Search_Engine_dsa](https://github.com/Ashu-Az/Search_Engine_dsa)** — a search engine written from scratch in JavaScript: TF-IDF scoring + cosine similarity, pure data structures & algorithms, no search libraries.
- 🧾 **[Affiliate_Management_System](https://github.com/Ashu-Az/Affiliate_Management_System)** — scalable affiliate platform: QR-code onboarding flow with a **superadmin → admin → affiliate → customer** role hierarchy.

## ⚙️ Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

## 📊 GitHub stats

![GitHub streak](https://streak-stats.demolab.com/?user=Ashu-Az&hide_border=true)

![Contribution graph](https://ghchart.rshah.org/40916b/Ashu-Az)

## 💬 Let's connect

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-40916b?style=flat&logo=vercel&logoColor=white)](https://portfolio-ivory-omega-17.vercel.app)
[![Email](https://img.shields.io/badge/Email-ashuazadblk%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ashuazadblk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashuazad-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashuazad/)
[![GitHub](https://img.shields.io/badge/GitHub-Ashu--Az-181717?style=flat&logo=github&logoColor=white)](https://github.com/Ashu-Az)
