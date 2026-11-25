<h1 align="center">Rafael Sánchez Cedillo</h1>

<p align="center">
  <strong>Director of Artificial Intelligence @ BuhoLegal</strong> · Physicist (M.Sc.) · Puebla, México
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rafael-sánchez-cedillo-75a50221b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:rscedillo35@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center"><em>"The purpose of computing is insight, not numbers." — Richard Hamming</em></p>

---

### About

Physicist working in AI and machine learning. As **Director of AI at BuhoLegal**, a Mexican
legal‑tech platform, I design, build and run the systems behind its search, data and
API products — from scraping and indexing court publications nationwide to semantic
search, LLM pipelines and the cloud infrastructure that serves them.

My physics background shapes how I approach ML: I care about models that are well
understood, not just well tuned — especially the connections between deep learning and
statistical mechanics.

### What I've built at BuhoLegal

**AI & search products**
- **AI case‑law search engine** ([tesis.buholegal.com](https://tesis.buholegal.com)) — designed and built end to end: hybrid exact + semantic search over ~312K Supreme Court theses (~1.85M vectors, Elasticsearch KNN), LLM query expansion, a weekly crawler of the official judicial gazette, and email alerts. Refactored from a monolith into a tested, CI‑backed service on Cloud Run.
- **Judicial search API** ([api.buholegal.com](https://api.buholegal.com)) — paid REST API over tens of millions of court records, plus CURP, RFC, SAT blacklist and federal‑edict lookups. Designed the unified `/v2` search shared by the API, the website and internal tools, and rebuilt identity lookups with Playwright when upstream sites added bot protection.
- **LLM document extraction API** — reads legal PDFs with AWS Textract and OpenAI agents, returns structured data, and bills per token.
- **RAG over constitutional & amparo law** — legal‑aware chunking, embeddings and a documented JSON API.

**Data & APIs**
- **Professional‑license API and state pipelines** — paid API (JWT, per‑user quotas) plus daily scraping jobs for state registries, indexed for search and SEO.
- **Case‑monitoring API** — rebuilt the API lawyers use to track their cases; hardened its security and optimized its heaviest queries.

**Infrastructure & platform**
- **Leading the migration of the main Elasticsearch cluster to Elastic Cloud** — wrote the proposal and built a single internal access layer with scoped keys and document‑level security.
- **Legacy modernization** — migrated a production legal‑alerts site from Python 2 / Django 1.2 to Python 3 / Django 4.2 on Cloud Run, and moved several services to Cloud Run with CI and separate test/prod environments.
- **Observability** — uptime and process monitoring, email deliverability tracking (SES), and database health dashboards for MySQL, Elasticsearch and MongoDB.
- **Admin platform** — major contributor to the internal Django system for customers, subscriptions, CFDI invoicing and payments: role‑based admin levels, data‑source status tracking, hourly business analytics and payment validation.

### Tech stack

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML & AI** &nbsp;
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Search & Data** &nbsp;
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Elastic Cloud](https://img.shields.io/badge/Elastic_Cloud-005571?style=flat-square&logo=elasticcloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Backend & Cloud** &nbsp;
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

**Tools** &nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Wolfram](https://img.shields.io/badge/Wolfram-DD1100?style=flat-square&logo=wolfram&logoColor=white)
