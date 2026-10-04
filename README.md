# Pablo Hoyos

**Data Science & AI student at Florida International University** · Seeking Summer 2027 internships in analytics and data engineering

I build data pipelines, analytics backends, and AI-assisted tools, and I care about the unglamorous parts: tests, validation, and systems that keep working after the demo. Bilingual (English / Español).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pablo_Hoyos-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/pablo-hoyos-4544b9383/)
[![Email](https://img.shields.io/badge/Email-phoyo008%40fiu.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:phoyo008@fiu.edu)

---

## What I work on

- **Data pipelines & ETL:** scheduled ingestion from third-party APIs and scraped sources, normalization, and loading into relational stores
- **SQL & data modeling:** PostgreSQL schemas, migrations, and query/RPC design for analytics dashboards
- **Reliability:** automated tests, data validation, and debugging production sync failures
- **Machine learning:** supervised classification and feature engineering (scikit-learn, Random Forest, XGBoost), model evaluation, and ML on physiological signals
- **Distributed data processing:** Apache Spark / PySpark
- **AI & agentic systems:** retrieval-augmented generation (RAG) with LLM APIs, and monitoring a production AI agent for ad-spend optimization

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**portfolio-tracker**](https://github.com/phoyo008/portfolio-tracker) | Ingests U.S. House and Senate trade disclosures (PDF and electronic filings), normalizes them, syncs a broker account, and produces copy-trade signals behind safety rails (paper/live modes, position caps, kill switch). Includes unit tests for the signal and safety logic. | Python, TypeScript, Alpaca API, pytest |
| [**lab-ipshyl**](https://github.com/phoyo008/lab-ipshyl) | Automates delivery of lab results for a healthcare clinic: parses patient data out of lab PDFs (including a defective-font workaround), matches patients to a Google Sheets directory, sends results by email, and keeps an audit log. | Python, Flask, SQLite, Google Sheets API |
| [**Stress-Detection-from-Cardiac-Signals**](https://github.com/phoyo008/Stress-Detection-from-Cardiac-Signals) | Classifies stress states from heart-rate variability features with a Random Forest (88% accuracy on the SWELL dataset) and a live-monitoring Streamlit dashboard. | Python, scikit-learn, Streamlit |
| [**AI-RAG-Chatbot**](https://github.com/phoyo008/AI-RAG-Chatbot) | Answers questions over uploaded documents using embeddings-based retrieval and Gemini, with a written reflection on responsible AI use. | Python, Streamlit, Gemini API |
| [**CAP2757**](https://github.com/phoyo008/CAP2757) | Exploratory data analysis and visualization of a real marine-environment dataset. | pandas, Plotly, Streamlit |

## Technical skills

| | |
|---|---|
| **Languages** | Python, SQL, TypeScript, Java |
| **Data** | Apache Spark, PySpark, pandas, NumPy, PostgreSQL / Supabase, SQLite, Jupyter |
| **Machine learning** | scikit-learn, XGBoost, Random Forest, feature engineering, model evaluation |
| **Backend & tooling** | Flask, REST APIs, pytest, Docker, Git / GitHub, pull-request review |
| **Cloud & deploy** | Vercel, Railway, Supabase |

## Experience highlights

- Maintain and extend the analytics backend of an e-commerce Amazon / Google Ads dashboard: data-sync jobs, SQL functions, and fixes for incorrect date-window and totals logic, delivered through pull requests and code review.
- Built internal tooling for a healthcare clinic in Colombia, automating a manual lab-results workflow end to end.

## Currently

Studying Data Science & AI at FIU and looking for a Summer 2027 internship in analytics or data engineering.
