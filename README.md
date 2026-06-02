<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=C9D1D9&center=true&vCenter=true&width=600&lines=Sergey+Kattsyn+%2F+phantom2059;ML+Engineer+%C2%B7+Competition+ML;Novosibirsk%2C+Russia" alt="Typing SVG" />

<br/>

[![Telegram](https://img.shields.io/badge/Telegram-@phantom2059-229ED9?style=flat-square&logo=telegram&logoColor=white)](https://t.me/phantom2059)
[![Kaggle](https://img.shields.io/badge/Kaggle-@phantom2059-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/phantom2059)

</div>

---

## Achievements

| Year | Competition | Result |
|------|------------|--------|
| 2026 | **NTO "Big Data & ML"** — Национальная технологическая олимпиада | 🥇 **1st place** team · **Top 8** individual |
| 2026 | **NTO "Artificial Intelligence"** | 🥈 **Prize winner** · individual standings |
| 2026 | **Data Fusion Contest 2026** — Companion · team ICEQ | 🥇 **Winner** · ₽50,000 prize pool|
| 2026 | **NEOAI 2026 National Selection** — Сбер Университет | **Finalist** · in-person selection round |
| 2025 | **TenderHack** — Novosibirsk | 🥇 **1st place** · ₽500,000 prize pool |
| 2025 | **Russian AI Olympiad** — Всероссийская олимпиада по ИИ | **Top 50 finalist** out of 55,000+ participants |
---

## Stack

<table>
<tr>
<td valign="top" width="33%">

**ML / Boosting**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-026E02?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EC3E1B?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

</td>
<td valign="top" width="33%">

**Deep Learning / LLM**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0866FF?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-4a4a4a?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</td>
<td valign="top" width="33%">

**Backend / Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Bitrix24](https://img.shields.io/badge/Bitrix24-001D6C?style=flat-square&logo=bitrix24&logoColor=white)

</td>
</tr>
</table>

---

## Projects

**[local-lua-cli](https://github.com/phantom2059/local-lua-cli)** &nbsp;·&nbsp; Autonomous Lua code agent · CLI
> Fine-tuned Qwen3-4B served via Ollama (or any compatible local model) · Generates, validates, lints and self-repairs Lua scripts · Fully local inference, no cloud

**[1st-place-NTO-BDiMO-2026](https://github.com/phantom2059/1st-place-NTO-BDiMO-2026)** &nbsp;·&nbsp; Extreme few-shot product classification · NTO BDiMO 2026 Finals
> 4582 categories, 1-3 samples each · Lookup cascade (~40% items, ~93% acc) + centroid kNN with 3-channel TF-IDF · Semi-supervised TF-IDF · Transductive anchors · **76.36% LB** · no GPU, scikit-learn only

**[9th-place-NTO-AI-2026](https://github.com/phantom2059/9th-place-NTO-AI-2026)** &nbsp;·&nbsp; Recommender system · NTO AI 2026 Finals · team ICEQ
> 4-pipeline ensemble blended via RRF · CatBoost YetiRank · LightGBM LambdaRank · CF ensemble (Item2Item, User2User, ALS-BM25) · EASE / ALS / SVD / ItemKNN candidates · ~250 hand-crafted features

**[ICEQ](https://github.com/phantom2059/ICEQ)** &nbsp;·&nbsp; Automatic question generation from large texts
> Fine-tuned T-lite-it-1.0 on custom QA dataset · FAISS clustering · DeepSeek / Qwen API · Flask web interface

**[data-fusion-guardian-ICEQ](https://github.com/phantom2059/data-fusion-guardian-ICEQ)** &nbsp;·&nbsp; Anti-fraud detection · Data Fusion 2026
> 150+ features · 4× CatBoost with product decomposition · CoLES contrastive pretraining · feedback-injection model

**[URL Detector](https://github.com/phantom2059/URL_detector)** &nbsp;·&nbsp; Phishing detection · end-to-end pipeline
> CatBoost → ONNX → Chrome Extension · **96.2% Acc · AUC 0.993** · 800k URLs · local WASM inference

**[RAG Pipeline](https://github.com/phantom2059/rag-pipeline-ru)** &nbsp;·&nbsp; Russian-language QA system
> Mistral-7B-Saiga · FAISS · 4/8-bit quantization · pymorphy2 lemmatization · CLI + Jupyter

**[Oral Exam Scorer](https://github.com/phantom2059/rasti_v_it)** &nbsp;·&nbsp; Automated grading · Hackathon "Расти в IT"
> Qwen2.5-VL-3B + LoRA fine-tune · RuBERT semantic similarity · 4-bit NF4 quantization

---

## Stats

<div align="center">

<img height="170" src="https://github-readme-streak-stats-salesp07.vercel.app?user=phantom2059&theme=github-dark-blue&hide_border=true&background=0d1117&date_format=j%20M%5B%20Y%5D&ring=4493F8&fire=4493F8&currStreakLabel=4493F8" />

</div>

<div align="center">

<img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=phantom2059&theme=github_dark&v=2" />
&nbsp;
<img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=phantom2059&theme=github_dark&utcOffset=7&v=2" />

</div>

---

<div align="center">

*Open to research collaborations*
</div>
