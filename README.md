# Hi, I'm Mujtaba Shahid

AI engineer and MS Artificial Intelligence student at NUST, Islamabad. I build LLM applications, retrieval-augmented generation (RAG) pipelines and data tools in Python.

> **Actively looking for AI / ML engineering roles.** Reach me at [mujtabashahid445@gmail.com](mailto:mujtabashahid445@gmail.com) or on [LinkedIn](https://linkedin.com/in/mujtabashahid).

- **Studying:** MS in Artificial Intelligence at NUST (machine learning, deep learning, computer vision)
- **Experience:** Power BI dashboards and reporting at Data BI, Python internships in automation and web scraping, and a year of computational biology research at the National Centre for Bioinformatics
- **Background:** BS in Bioinformatics from Quaid-i-Azam University
- **Interested in:** grounded LLM systems, retrieval and reranking, agent workflows with LangGraph, applied ML on health data, and self-hosted infrastructure

---

## Featured projects

### [PharmRAG](https://github.com/MujtabaGit56/PharmRAG): medication Q&A grounded in FDA drug labels

A retrieval-augmented system that answers medication questions using only FDA-approved drug label text, so every answer can be traced back to its source.

- Built over ~100K OpenFDA drug labels, indexed with FAISS
- Multi-stage retrieval: drug detection, query intent classification, drug-aware filtering, section-priority boosting and cross-encoder reranking
- Compared general-purpose and medical-domain embeddings; the medical embeddings beat both the general model and an ungrounded LLM baseline on factuality, safety coverage and clarity across 150 consumer questions
- Answers generated with Gemini 2.5 Flash, served through a Streamlit interface that shows the retrieved sources

`Python` `FAISS` `BGE embeddings` `Cross-encoder reranking` `Gemini` `Streamlit`

### [Artemis Homelab](https://github.com/MujtabaGit56/artemis-homelab): self-hosted home server

A home server I built and run on a Proxmox mini PC: about 15 services in Docker, split into a media container and a separate, locked-down one for passwords and finance.

- Remote access through Tailscale with no ports open to the internet
- Encrypted offsite backups with email alerts when one fails
- A Python service that reads bank transaction emails and adds them to my finance app

`Proxmox VE` `Docker Compose` `Tailscale` `Python` `Bash`

---

## Other work

| Project | What it does | Stack |
|---|---|---|
| **Unified Bioinformatics Web Tool** | One web interface for sequence alignment, motif analysis and phylogenetic trees, with multi-step analyses chained into automated workflows | Flask, BioPython, Pandas, Matplotlib |
| **Cancer Genomics Analysis (KIRC)** | Multi-omics analysis of 512 kidney tumour samples from TCGA; survival curves, volcano plots and pathway maps pointing to MTOR and SF3B1 as key drivers | Python, R, cBioPortal |

---

## Tech stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**AI / ML:**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Data & apps:**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Infrastructure:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mujtabashahid-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mujtabashahid)
[![Email](https://img.shields.io/badge/Email-mujtabashahid445%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mujtabashahid445@gmail.com)
