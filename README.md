# Daniel Alpeñes

**Data Engineer** · Spark · dbt · CDC · Python — Valencia, Spain

MSc student in Artificial Intelligence & Big Data at Universitat Politècnica de València (UPV), finishing my master's thesis. BSc in Computer Engineering (UPV, 2025).

I build data pipelines end to end (batch and streaming ingestion, modelling, data quality and serving) and the ML and LLM layer on top, reproducible with Docker and tested in CI. Open to Data Engineering roles.

[LinkedIn](https://www.linkedin.com/in/daniel-alpenes-de-lucca/)

## Experience

- **Data Scientist** · Solver Intelligent Analytics · Jan–Jul 2026 — Built all data ingestion and cleaning for a subscription product: ETL pipelines over 600M+ rows on AWS Redshift with Polars. Trained about 20 XGBoost models and built the FastAPI service that serves them.
- **Python Developer** · Solver Intelligent Analytics · Sep 2025–Jan 2026 — Automated API testing platform in Django for a banking-sector client, replacing manual regression checks.
- **Data & Software Intern** · Generalitat Valenciana · Feb–Jun 2025 — Built [RAG-TEND](https://github.com/Oppen-OC/RAG-TEND-TFG) solo, my bachelor's thesis: tender scraping, RAG extraction of 47 fields into SQL Server and a Django dashboard.
- **Software Intern** · PROYECO · Jul–Sep 2024 — Streamlit and LangChain tool that reads tender PDFs (OCR for scans) and fills an internal tender sheet automatically.

## Featured projects

- **[TFM](https://github.com/Oppen-OC/TFM)** — Master's thesis. Delay prediction for València's urban buses: streaming ingestion of the EMT fleet's GPS and live traffic, DuckDB ETL, a reproducible DVC + MLflow pipeline, and an XGBoost model served with FastAPI and a Streamlit UI.
- **[cdc-pipeline](https://github.com/Oppen-OC/cdc-pipeline)** — Streaming change data capture. PostgreSQL changes read from the WAL with Debezium, moved through Redis Streams, enriched and materialised idempotently (LSN guard, at-least-once delivery with exactly-once effect), and served with FastAPI. End-to-end test in CI.
- **[olist-medallion-dbt](https://github.com/Oppen-OC/olist-medallion-dbt)** — Bronze/silver/gold pipeline on ~100k real e-commerce orders with dbt and DuckDB: data-quality tests, enforced gold contracts, CI and published lineage docs.
- **[iot-streaming-delta-lake](https://github.com/Oppen-OC/iot-streaming-delta-lake)** — Real-time vehicle telemetry with Spark Structured Streaming: six cleaning rules, a quarantine table and city-partitioned Delta Lake tables on Databricks, plus a local PySpark version.
- **[RAG-TEND-TFG](https://github.com/Oppen-OC/RAG-TEND-TFG)** — Bachelor's thesis. Scrapes Spanish public tenders and extracts 47 structured fields with RAG + Llama 3.3 into SQL Server for analytics.
- **[finanzas](https://github.com/Oppen-OC/finanzas)** — Local-first personal finance ledger for Spanish bank exports: idempotent import, LLM-written categorisation rules, metrics and scenarios. FastAPI + SQLite + htmx.

## Stack

- **Languages:** Python, SQL, C, Bash
- **Data engineering:** Spark (Structured Streaming), dbt, DuckDB, Polars, pandas, PostgreSQL, AWS Redshift, Delta Lake, Debezium, Redis Streams, SQL Server
- **ML / AI:** XGBoost, LightGBM, Optuna, MLflow, DVC, LangChain, RAG
- **Platforms & tooling:** Docker, GitHub Actions, Databricks, FastAPI, Django, Streamlit
