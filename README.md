# Vishwas Prabhakara

### Applied Machine Learning Engineer

I build and evaluate machine-learning systems for real-world data problems, with a focus on **time-series forecasting, environmental data, retrieval systems, and deployable Python applications**.

My current work at the **Centre for Sustainable Technologies, Indian Institute of Science (IISc)** includes groundwater monitoring and forecasting for Bengaluru. I care about leakage-safe evaluation, strong baselines, reproducible experiments, and choosing the simplest model that performs reliably on unseen data.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vishwas_Prabhakara-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/vishwas-prabhakara/)
[![Email](https://img.shields.io/badge/Email-vp14032001%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vp14032001@gmail.com)
[![Location](https://img.shields.io/badge/Location-Bengaluru%2C_India-2E7D32?style=flat)](https://www.google.com/maps/place/Bengaluru)

---

## Selected Work

### [Bengaluru Groundwater Forecasting](https://github.com/VishwasPrabhakara/Groundwater_Outlook_For_Bengaluru)

Confidential applied-ML project for six-month groundwater-level forecasting across selected Bengaluru wards. The public repository documents the methodology and aggregate results without exposing institutional data, source code, ward identifiers, or trained artifacts.

- 37 wards and 3,552 monthly ward observations from 2016-2023
- Leakage-safe fixed-origin temporal backtesting
- Three development forecast origins and an untouched January-June 2023 final test
- Compared Ridge, XGBoost, a heterogeneous stack, and statistical baselines
- Ridge was selected on development stability and achieved **R² 0.606**, **MAE 3.63 m**, and **RMSE 6.08 m** on 222 final-test predictions
- Analysis showed that forecast error increased materially beyond the three-month horizon

`Time-series forecasting` `Temporal validation` `scikit-learn` `XGBoost` `Environmental ML`

---

### [STIS-V Conference Platform](https://github.com/VishwasPrabhakara/STISV)

Full-stack conference workflow platform developed for STIS-V 2025 at IISc.

- React frontend with a Node.js and Express backend
- Supported conference information and participant-facing workflows
- Included document-generation and submission-related functionality
- Separate [backend repository](https://github.com/VishwasPrabhakara/STISV_Server)

`React` `Node.js` `Express` `REST APIs`

---

### [DataLens](https://github.com/VishwasPrabhakara/datalens)

Natural-language interface for querying relational databases with schema-aware retrieval, SQL generation, validation, correction, and chart generation.

- Retrieves relevant schema context instead of placing the entire database schema in every prompt
- Validates generated SQL before execution
- Includes automated tests for retrieval, profiling, SQL generation, validation, and correction
- Supports local SQLite workflows and database exploration through a Streamlit interface

`Python` `SQL` `LangChain` `Gemini` `FAISS` `sqlglot` `Streamlit`

---

### [PaperLens](https://github.com/VishwasPrabhakara/Chat_with_PDF)

Hybrid retrieval-augmented generation system for question answering over PDF documents.

- Combines dense FAISS retrieval with BM25 lexical retrieval
- Uses Reciprocal Rank Fusion and cross-encoder reranking
- Produces grounded responses with source citations
- Separates document processing, retrieval, prompting, and application logic

`Python` `RAG` `FAISS` `BM25` `Cross-encoder reranking` `Streamlit`

---

### [Sutra](https://github.com/VishwasPrabhakara/sutra)

Multi-agent assistant built for the Gen AI Hackathon APAC 2026.

- Coordinates specialized agents through tool and function calling
- Includes streaming responses, memory, and Google Workspace integrations
- Uses a FastAPI backend and React/TypeScript frontend
- Packaged as an end-to-end cloud application

`Python` `FastAPI` `Gemini` `React` `TypeScript` `Google Cloud`

---

## Engineering Focus

| Area | Tools and practices |
|---|---|
| Machine learning | Python, pandas, NumPy, scikit-learn, XGBoost, feature engineering, baseline design |
| Evaluation | Temporal backtesting, leakage prevention, error analysis, model comparison |
| LLM systems | Retrieval-augmented generation, hybrid search, reranking, tool calling, structured outputs |
| Backend and deployment | FastAPI, REST APIs, Docker, Google Cloud Run |
| Data and visualization | SQL, PostgreSQL, Plotly, geospatial and environmental data |
| Frontend | React, TypeScript, Streamlit |

## How I Work

- Start with a measurable problem and a strong baseline
- Keep training and evaluation boundaries explicit
- Treat complex models as candidates, not automatic winners
- Document limitations and failure modes alongside headline metrics
- Separate exploratory notebooks from reusable application code
- Avoid publishing confidential data or implementation details

## Background

- Working on applied machine learning at the **Centre for Sustainable Technologies, IISc**
- Master's degree in **Artificial Intelligence and Machine Learning**
- Presented project and research work at **IISc Open Day** and **MPRiSIM 2025**
- Participated in the **Google Cloud Gen AI Academy, APAC 2026**

## Contact

I am open to applied ML and ML engineering opportunities involving forecasting, data-intensive systems, environmental applications, or reliable LLM products.

- **Location:** Bengaluru, India
- **Email:** [vp14032001@gmail.com](mailto:vp14032001@gmail.com)
- **LinkedIn:** [linkedin.com/in/vishwas-prabhakara-2050821b6](https://www.linkedin.com/in/vishwas-prabhakara-2050821b6/)
