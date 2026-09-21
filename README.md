# Hi, I'm Sanjay.

I build end-to-end analytics and AI systems - clean data in, dashboards and grounded decisions out. Most of my work sits at the intersection of BI (Power BI), analytics engineering (SQL + Python), and applied ML/LLM systems when they add real value.

Top Projects:

- Levi's RAG - AI due diligence copilot, retrieval-grounded answers over SEC filings, deployed FastAPI + Next.js ([Repo](https://github.com/sanjay-dilip/levis-rag))
- NBA Win Probability Engine - pre-game and live win-probability model, deployed Streamlit dashboard ([Repo](https://github.com/sanjay-dilip/nba-win-probability-engine))
- Intelligent AI Workflow Automation - workflow-risk classifier paired with a fully separate, deterministic rules/KPI engine, live Streamlit dashboard ([Repo](https://github.com/sanjay-dilip/intelligent-ai-workflow-automation))
- Supply Chain Disruption Analytics - Azure pipeline validating delay drivers statistically before predicting order-time delay risk ([Repo](https://github.com/sanjay-dilip/supply-chain-disruption-analytics))
- Drug Interaction Checker - CLI tool where every interaction fact comes from a curated dataset, never inferred; an optional LLM can only reword an already-retrieved fact ([Repo](https://github.com/sanjay-dilip/drug-interaction-checker))
- Property Listing Generator - deterministic comp-analysis engine picks genuine differentiators first; an optional LLM only phrases facts it's handed, checked by a fair-housing safety validator ([Repo](https://github.com/sanjay-dilip/property-listing-generator))
- Sim2Real Engagement - sim vs real churn signals, Streamlit comparison dashboard ([Repo](https://github.com/sanjay-dilip/sim2real-engagement))
- WC2026 Format Evaluation - statistical evaluation of FIFA's 48-team World Cup expansion on competitive balance and fairness, Snowflake pipeline + Power BI dashboard ([Repo](https://github.com/sanjay-dilip/wc2026-format-eval))

## What I work on
- DA/BI: Power BI (DAX), Tableau, KPI reporting, dashboard storytelling
- Analytics: SQL, Python (pandas), experimentation, forecasting
- Data Engineering: ETL/ELT, curated layers (Parquet), data modeling, quality checks
- ML/AI: NLP, recommenders/ranking, RAG pipelines, LLM agents, model evaluation, deployment (FastAPI, Streamlit) - a recurring pattern across several of these is keeping a deterministic core in charge of every fact and number, with the LLM restricted to explaining or rewording what it's handed, never computing or inventing

## Highlights
- I like projects where metrics tie to real decisions (late delivery risk, churn risk, ranking quality).
- I care about reproducibility: clear READMEs, runnable steps, and basic checks.

## Current Focus
- Building retrieval-grounded and agentic AI systems with evaluation checks, not just demos (Levi's RAG, InsightPilot)
- Building multi-agent, evidence-grounded investigation systems where an LLM narrates but never computes a number (MetricTrace)
- Shipping full ML apps end-to-end: model, evaluation, and a live deployed dashboard (NBA Win Probability Engine)
- Strengthening data engineering habits: curated layers, data checks, and clean project structure
- Keeping project READMEs and CI (GitHub Actions) current as each project ships

## Tools I use
SQL, Power BI, Excel, Python (pandas, scikit-learn), Streamlit, FastAPI, LLM APIs (OpenAI, Gemini, Hugging Face Inference), RAG/vector search, DuckDB, Snowflake, Azure (ADF/Blob), GitHub Actions

## Ongoing Projects
- MetricTrace: Multi-Agent KPI Dispute Resolver — An investigation copilot that reconciles a known KPI discrepancy between two dashboards into an evidence-backed, dollar-attributed explanation, computed by deterministic SQL/data-quality tools and only narrated by an LLM. In development (135/135 tests passing; benchmark and evaluation harness in progress). Private for now.

## Contact
- Email: [sanjay.dilip3012@gmail.com](mailto:sanjay.dilip3012@gmail.com)
- LinkedIn: [Sanjay Dilip](https://www.linkedin.com/in/sanjaydilip)

Outside of work, I like digging into sports, film, and world-event datasets, and increasingly building small AI agents to help make sense of them.
