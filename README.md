<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Jenish+J+%F0%9F%91%8B;Full+Stack+%26+AI+Engineer;Building+systems+that+actually+ship." alt="Typing SVG" />

<br/>

*4th Year CS @ Panimalar Engineering College · AI Engineer Intern @ Zuntra Digital*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jenishj-dev)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR_SITE)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jenishj436@gmail.com)

</div>

---

## About Me

<img align="right" width="360" src="https://i.pinimg.com/originals/47/f0/34/47f0342cec72b800463bf003eac1257e.gif"/>

I build at the intersection of **full-stack engineering and applied AI** — from production RL environments to LLM-powered platforms.

Currently shipping **HireMind AI** at Zuntra Digital: an end-to-end AI recruitment platform that automates up to 95% of the hiring pipeline using Gemini, RAG, and semantic candidate matching.

I gravitate toward problems with no clean off-the-shelf answer — the kind where you have to design the environment before you can even start solving.

- 🔭 Working on **LLM agent evaluation frameworks** and **RL environments**
- 🌱 Deepening expertise in **multi-agent systems** and **production ML infra**
- 🤝 Open source contributor — see pinned repos below
- ⚡ Fun fact: I can explain Reinforcement Learning using a supply chain crisis

<br clear="right"/>

---

## 🛠️ Tech Stack

### Languages
<p>
<img height="45" width="45" src="https://img.icons8.com/color/48/python.png" title="Python"/>
<img height="45" width="45" src="https://img.icons8.com/color/48/javascript.png" title="JavaScript"/>
<img height="45" width="45" src="https://img.icons8.com/color/48/typescript.png" title="TypeScript"/>
</p>

### Frontend
<p>
<img height="45" width="45" src="https://img.icons8.com/color/48/react-native.png" title="React"/>
<img height="45" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" title="Next.js"/>
<img height="45" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" title="Tailwind"/>
</p>

### Backend & APIs
<p>
<img height="45" width="45" src="https://img.icons8.com/color/48/nodejs.png" title="Node.js"/>
<img height="45" src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
</p>

### AI / ML
<p>
<img height="45" src="https://img.shields.io/badge/LLM_APIs_(Gemini,_OpenAI,_Llama)-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge&logo=databricks&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/Reinforcement_Learning-00897B?style=for-the-badge&logo=scipy&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/Stable--Baselines3-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
</p>

### Databases
<p>
<img height="45" width="45" src="https://img.icons8.com/color/48/mongodb.png" title="MongoDB"/>
<img height="45" width="45" src="https://img.icons8.com/color/48/mysql-logo.png" title="MySQL"/>
<img height="45" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### Cloud & DevOps
<p>
<img height="45" src="https://img.shields.io/badge/Google_Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img height="45" src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

### Tools
<p>
<img height="45" width="45" src="https://img.icons8.com/color/48/visual-studio-code-2019.png" title="VS Code"/>
<img height="45" width="45" src="https://img.icons8.com/color/50/git.png" title="Git"/>
<img height="45" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

---

## 🚀 Featured Projects

### [OncoEnv](https://github.com/YOUR_HANDLE/OncoEnv) — Bioinformatics RL Environment

A production-grade RL environment for autonomous LLM agent evaluation across single-cell RNA analysis workflows — built from scratch in NumPy/SciPy to eliminate heavy library dependencies.

- **40+ discrete actions** spanning QC, PCA, Leiden clustering, Wilcoxon DE, and GRN inference
- **3 progressive difficulty tiers** graded by IoU, nDCG, AUROC/AUPRC
- Identified and fixed a critical reward-signal bug from overlapping mitochondrial gene / TF indices — directly improved baseline LLM agent performance
- Concurrent FastAPI backend with **LRU TTL session caching** and WebSocket support for simultaneous agent evaluation

`Python` `NumPy` `SciPy` `FastAPI` `WebSockets` `RL`

---

### [GlobalProcurementEnv](https://github.com/YOUR_HANDLE/GlobalProcurementEnv) — Supply Chain RL Agent

OpenEnv Hackathon submission: a multi-country supply-chain RL environment where an AI agent navigates real trade policies and live disruptions.

- Real trade policy modelling across **India, EU, USA** — port strikes, sanctions, protests
- Multi-objective reward: compliance · cost · delivery · carbon
- PPO agent via Stable-Baselines3 + LLM inference agent via Llama-3.3-70B
- Deployed on Hugging Face Spaces · **500+ episodes · 0 failures · ~160 eps/sec**

`Python` `Stable-Baselines3` `PPO` `Llama-3.3-70B` `Hugging Face` `Docker`

---

### [CrackTheVault](https://github.com/YOUR_HANDLE/CrackTheVault) — LLM Security Game

Microservices-based game where players attempt prompt injection attacks against a defended LLM system — built for a college symposium.

- 3 FastAPI services (API Gateway, Policy Engine, DB Service) via Docker Compose
- **5-layer prompt injection defence**: regex filter → rule detection → rate limiting → adaptive difficulty → threshold escalation
- LLM-powered argument scoring with NLP classification

`FastAPI` `Docker Compose` `NLP` `LLM Security` `Microservices`

---

## 💼 Experience

**AI Engineer Intern** · [Zuntra Digital](https://zuntradigital.com) *(Sep 2025 – Present)*

Building HireMind AI — an end-to-end AI recruitment platform:
- Architected ATS resume screening, candidate ranking, and AI-powered interview pipelines automating **~95% of the hiring workflow**
- Built an LLM evaluation pipeline on **Google Vertex AI (Gemini)** with RAG retrieval, resume parsing, and dynamic interview question generation
- Designed REST APIs enabling semantic candidate retrieval and automated interview orchestration across concurrent hiring pipelines

---

## 📊 GitHub Stats

<div align="center">


![Jenish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=JEN-chad)]

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JEN-chad&layout=compact&theme=dark&hide_border=true)

</div>

---

## 🧩 LeetCode

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/Jenish_coder?ext=contest&theme=dark)](https://leetcode.com/YOUR_LEETCODE_HANDLE)

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Jenish's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=JEN-chad&bg_color=000000&color=ffffff&line=6E40C9&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

**Open to SWE · AI/ML · Founding Engineer roles — full-time or internship**

[jenish@email.com](mailto:jenishj436@gmail.com) · [linkedin.com/in/YOUR_HANDLE](https://linkedin.com/in/jenishj-dev)

</div>
