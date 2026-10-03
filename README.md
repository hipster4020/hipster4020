<div align="center">

<img src="assets/profile.jpg" width="200" alt="SeongHwan Park" />

# SeongHwan Park

**AI Agent Engineer / LLM Application Developer**

[![Gmail](https://img.shields.io/badge/Gmail-hipster4020@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hipster4020@gmail.com)
[![Blog](https://img.shields.io/badge/Blog-Tistory-000000?style=flat-square&logo=tistory&logoColor=white)](https://hipster4020.tistory.com/)
[![GitHub](https://img.shields.io/badge/GitHub-hipster4020-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hipster4020)
[![PyPI](https://img.shields.io/badge/PyPI-pshmodule-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/pshmodule/)

</div>

---

## 👋🏻 About Me

| Field | Experience |
|---|---|
| 🤖 NLP · Chatbot | **5 yrs 9 mos** |
| ☕ Java · Oracle | **3 yrs 7 mos** |
| 📊 Data Analysis | **1 yr 8 mos** |

I build LLM applications end to end — from deep-learning NLP modeling to planning, developing and deploying RAG and multi-agent chatbots.

- **Engineering is not a solo sport.** — *"If you can't teach it, you don't know it."*<br>
  I've led DL model planning and AWS pipeline builds together with planners, infra, back-end and non-technical partners.
- **Business growth is my growth.**<br>
  Better modeling means better services for users — that's where I grow.
- **I modularize everything.**<br>
  I packaged my most-used functions and published them to PyPI → [`pshmodule`](https://github.com/hipster4020/pshmodule)

---

## 🛠 Tech Stack

**Core**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Vector · Graph · Data**<br>
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Deep Learning**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Lightning](https://img.shields.io/badge/PyTorch_Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Infra · Tools**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Kubeflow](https://img.shields.io/badge/Kubeflow-326CE5?style=flat-square&logo=kubeflow&logoColor=white)
![W&B](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

---

## 💼 Career

### 🥬 Pulmuone — BX AI Team / AI Agent Engineer
`2023.09 ~ Present`

**HR AI Assistant Chatbot — RAG** *(Lead Developer)*
- Built an HR Q&A chatbot: GPT-based classification routes each question to a primary category, then an open-source model answers via RAG.
- Owned product planning end to end — document upload page, chat UI and DB design.

**Multi-Agent Chatbots — Modular RAG on LangGraph** *(Lead Developer & Planner)*
- **Sales Assistant** — Text2SQL pipeline generating queries from metadata, glossary and question–query examples; led planning of the admin page, chat UI, DB and model API deployment.
- **Indirect Procurement Contract Agent** — Scenario branching (classification → RAG → answer) with nodes for contract-category recommendation, purchase requests and POs; served via FastAPI in production.
- Also shipped legal/regulatory and factory-tour bots, plus a reusable chatbot UI template integrated with n8n workflows.

**AICC Voice Bot — Assistant API** *(Lead Developer)*
- Intent classification mapped to resolution actions; completed the full call-center flow (call → operation → STT → LLM → TTS).

### 📝 TEXTNET — TF Team / Modeler
`2022.11 ~ 2023.09`

- **Ad Copy Generation Reflecting Selling Points** — Extracted selling points via ChatGPT prompt tuning, converted writing style with T5, and fine-tuned Koalpaca-Polyglot (PEFT LoRA, instruction format) to generate ad copy matched to a selling point and MBTI type.
- **Personalized Ad Message Generation by Personality Type** — Collaborated with a major domestic retail group to re-implement a model that tailors ad messages to each personality type's style.
- **Meme Bot** — SBERT cosine-similarity retrieval with an LLM fallback; data augmentation via Korean eojeol/final-consonant EDA and pretrained-model style transfer.

### 📈 Illunex — AI Team / Senior Engineer
`2021.02 ~ 2022.11`

- **Category Classification** — Article classifier on Transformer encoder outputs, with an AWS pipeline writing predictions into MariaDB.
- **Sentiment Analysis with Active Learning** — Applied Learning Loss for Active Learning to a KoELECTRA positive/negative/neutral classifier, cutting manual annotation effort.
- **Named Entity Recognition** — BERT-based NER on the KLUE NER dataset to extract company names from article bodies.
- **Keyword Extraction & News Crawling** — KeyBERT keyword pipeline plus a Dockerized Selenium XPath crawler for news and startup sites.

### 📚 FutureNuri — Dev1 Team / Assistant Manager
`2017.06 ~ 2021.01`

- Data analysis and migration for a library automation solution used by public and university libraries.
- Owned the acquisitions, serials and reserved-books modules (back-end & front-end) and Oracle DB data migration.

---

## 📄 Paper

**When Can You Trust an Agent's Own Verifier?** — Stress-Testing Counterfactual Rationale Verification Under Search Pressure and Oracle Access<br>
`NeurIPS 2026 Workshop (non-archival)`

> Proposed a stress-testing protocol for label-free agent verifiers under optimization pressure — a pressure ratio ρ quantifying how strongly a verifier steers agent search, plus falsifiable probes for distinct failure modes (no signal, weak influence, claim-minimization, pre-commit query access). Evaluated the Rationale Consistency Score (RCS) in an LLM agent designing ML pipelines, with a capability-control experiment separating agent capability from search failure.

---

## 📘 Book

<table>
<tr>
<td width="200"><img src="assets/book.jpg" width="180" alt="Hugging Face Transformers Hard Training for NLP" /></td>
<td>

**Hugging Face Transformers Hard Training for Natural Language Processing**<br>
🏅 **Sejong Book Award 2025 — Selected Title**<br>
BJPublic

A hands-on guide to Hugging Face for NLP, built around practice code and its results so readers understand language models and transformers through the library's own features.

[📖 Kyobo Book](https://product.kyobobook.co.kr)

</td>
</tr>
</table>

---

## 🎤 Special Lectures

<img src="assets/lecture.jpg" width="360" alt="Special lecture at Gangneung-Wonju National University" />

- **Gangneung-Wonju National University**, Dept. of Data Science — special lecture on AI & data analysis, *"How to Build Your Own Competitive Edge in the LLM Era"*
- **Namseoul University**, Dept. of Distribution & Marketing — special lecture on AI & data analysis

---

## 🎓 Education

- **M.Eng. in Artificial Intelligence (in progress)** — Yonsei University, Graduate School of Engineering · `2026.02 ~`
- **B.S. in Information & Statistics** — Gangneung-Wonju National University · `2008.03 ~ 2015.02`

## 📜 Certificates

- `2019.04` SQLD — Korea Data Agency
- `2017.05` Engineer Information Processing — HRD Korea
- `2014.08` Social Survey Analyst Level 2 — HRD Korea

---

## 🗂 Featured Repositories

| Repository | Description |
|---|---|
| [pshmodule](https://github.com/hipster4020/pshmodule) | Utility package for preprocessing, file I/O and crawling (PyPI) |
| [sentiment_classification](https://github.com/hipster4020/sentiment_classification) | KoELECTRA sentiment classification with active learning |
| [encoder_classifier_with_pl](https://github.com/hipster4020/encoder_classifier_with_pl) | Transformer encoder classifier with PyTorch Lightning |
| [category_classification](https://github.com/hipster4020/category_classification) | Article category classification |
| [keybert](https://github.com/hipster4020/keybert) | Keyword extraction with KeyBERT |

<div align="center">

<br>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hipster4020&show_icons=true&hide_border=true)

</div>
