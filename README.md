<div align="center">

# Hi, I'm Vishwas 👋

**Machine Learning Engineer @ Indian Institute of Science (IISc)** <br />
Building ML systems where the data is messy, the stakes are real, and the model has to work outside a notebook.

![Profile views](https://komarev.com/ghpvc/?username=VishwasPrabhakara&color=blueviolet&style=flat&label=Profile+Views)

</div>

---

I work at the **Centre for Sustainable Technologies, IISc**, building groundwater monitoring and forecasting systems for Bengaluru — in collaboration with **BWSSB**. On the side, I build multi-agent AI systems, LLM tooling, and cloud-deployed ML services.

**📬 Open to opportunities — full-time roles in Bengaluru, Hyderabad, or Chennai, remote positions, and freelance projects.**
Reach me at **vp14032001@gmail.com**.

---

### 🔭 What I'm working on right now

- **Groundwater Level Prediction (IISc × BWSSB)** — Time-series + geospatial ML across 100+ Bengaluru wards. R² up to 0.9 with two-stage feature selection (Pearson + Mutual Information).
- **Sensor Data Pipeline (KrushiHrudaya)** — Rolling-MAD spike detection, UID-level noise classification, and automated CGWB-style reporting for 193+ active sensors.
- **[Sutra](https://github.com/VishwasPrabhakara/sutra)** — A multi-agent AI chief-of-staff. 6 specialized sub-agents orchestrated via Gemini function calling. Built solo for Google Cloud Gen AI Academy APAC Hackathon 2026.
- **DataLens** (just shipped) — Chat-with-your-database with 5-agent SQL pipeline and self-correcting validation. Same "Lens" architecture as PaperLens, different data source.
- **Applying to ML Engineer roles** — Bengaluru, Hyderabad, Chennai, or remote. [Reach me](mailto:vp14032001@gmail.com).

---

### 🛠️ Tech Stack

**ML & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**LLMs & Agents**
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)

**Backend & Cloud**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Frontend & Geo**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

---
### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 💧 [Groundwater Forecasting (IISc × BWSSB)](https://github.com/VishwasPrabhakara/Groundwater_Outlook_For_Bengaluru)
Time-series + geospatial ML predicting groundwater levels across 100+ Bengaluru wards. R² up to 0.9 with two-stage feature selection (Pearson + MI), ablation across lags, climate, built-up area, seasonality.

**Stack:** Python · scikit-learn · pandas · GeoJSON · Leaflet · Chart.js

</td>
<td width="50%" valign="top">

#### 🧠 [Sutra](https://github.com/VishwasPrabhakara/sutra)
Multi-agent AI chief-of-staff with 6 specialized sub-agents orchestrated via Gemini function calling. FastAPI + Cloud Run backend, React/TypeScript frontend, SQLite persistence.

**Stack:** Python · FastAPI · Gemini · React · TypeScript · GCP  <br/>
**Live:** https://sutra-frontend-381066349460.us-central1.run.app

</td>
</tr>

<tr>
<td width="50%" valign="top">

#### 📄 [PaperLens](https://github.com/VishwasPrabhakara/Chat_with_PDF)
Hybrid-retrieval RAG over PDFs. FAISS + BM25 fused via Reciprocal Rank Fusion, cross-encoder reranking, and Gemini for grounded answers with `[N]` citations.

**Stack:** Python · Streamlit · LangChain · Gemini · FAISS · BM25  <br />
**Live:** https://vishwas-paperlens-chat-with-pdf.streamlit.app/

</td>
<td width="50%" valign="top">

#### 📊 [DataLens](https://github.com/VishwasPrabhakara/datalens)
Chat with any database. 5-agent SQL pipeline (Schema → SQL → Validator → Corrector → Insight). Self-correcting SQL validation via `sqlglot` + EXPLAIN dry-runs. Bring your own SQLite or Postgres URI.

**Stack:** Python · Streamlit · LangChain · Gemini · FAISS · sqlglot · Plotly <br/>
**Live:** https://vishwas-datalens-chat-with-database.streamlit.app/

</td>
</tr>

<tr>
<td width="50%" valign="top">

#### 💱 [CurrencyBot](https://github.com/VishwasPrabhakara/currency-bot)
ADK + MCP agent on the Frankfurter API. Real-time rates, conversions, historical lookups, trend analysis. Embedded MCP server in a single Cloud Run container.

**Stack:** Python · Google ADK · MCP · Gemini · Cloud Run <br/>
**Live** https://currency-agent-381066349460.us-central1.run.app/dev-ui/

</td>
<td width="50%" valign="top">

#### 📝 [SmartText Agent](https://github.com/VishwasPrabhakara/smart-text-agent)
Five text-processing capabilities (summarize, Q&A, classify, analyze, route) unified under one Gemini-powered ADK agent with intent routing.

**Stack:** Python · Google ADK · Gemini · Cloud Run <br/>
**Live:** https://smart-text-agent-381066349460.us-central1.run.app/dev-ui/

</td>
</tr>
</table>

### Other work

#### [STISV](https://github.com/VishwasPrabhakara/STISV_Server)

Production conference management platform developed for STIS-V 2025 at IISc.

**Tech Stack:** React, Node.js, Express, MongoDB  
**Features:** PDF generation, conference workflow management  

---

### 📊 GitHub Stats

<table>
<tr>
<td>
<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=VishwasPrabhakara&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
</td>
<td>
<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=VishwasPrabhakara&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=html,css,jupyter%20notebook" />
</td>
</tr>
</table>

<img src="https://github-readme-streak-stats-eight.vercel.app?user=VishwasPrabhakara&theme=tokyonight&hide_border=true" />

---

### 🎓 Credentials

- **Google Cloud Gen AI Academy** — APAC 2026, Cohort 1
- **M.Tech in AI & ML** — Manipal School of Information Sciences
- Presented research at **IISc Open Day** and **MPRiSIM 2025** conference

---

### 📫 Let's talk

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vp14032001@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishwas-prabhakara-2050821b6/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VishwasPrabhakara)

**Location:** Bengaluru, India <br/>
**Open to:** Full-time roles in Bengaluru · Hyderabad · Chennai · Remote · Freelance

If you're hiring, freelancing, or just want to nerd out about agents, geospatial ML, or how to keep a sensor network honest — drop a line.
---

<div align="center">

*Building ML systems where the data is messy, the stakes are real, and the model has to work outside a notebook.*

</div>
