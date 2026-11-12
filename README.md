# Daniel Alpeñes

**Data Engineer** · Spark · dbt · CDC · Python — Valencia, Spain

MSc student in Artificial Intelligence & Big Data at Universitat Politècnica de València (UPV), finishing my master's thesis. BSc in Computer Engineering (UPV, 2025).

I build data pipelines end to end: batch and streaming ingestion, modelling, data quality and serving, reproducible with Docker and tested in CI. Open to Data Engineering roles.

[LinkedIn](https://www.linkedin.com/in/daniel-alpenes-de-lucca/)

## Featured projects

- **[TFM](https://github.com/Oppen-OC/TFM)** — Master's thesis. Delay prediction for València's urban buses: streaming ingestion of the EMT fleet's GPS and live traffic, DuckDB ETL, a reproducible DVC + MLflow pipeline, and an XGBoost model served with FastAPI and a Streamlit UI.
- **[cdc-pipeline](https://github.com/Oppen-OC/cdc-pipeline)** — Streaming change data capture. PostgreSQL changes read from the WAL with Debezium, moved through Redis Streams, enriched and materialised idempotently (LSN guard, at-least-once delivery with exactly-once effect), and served with FastAPI. End-to-end test in CI.
- **[olist-medallion-dbt](https://github.com/Oppen-OC/olist-medallion-dbt)** — Bronze/silver/gold pipeline on ~100k real e-commerce orders with dbt and DuckDB: data-quality tests, enforced gold contracts, CI and published lineage docs.
- **[iot-streaming-delta-lake](https://github.com/Oppen-OC/iot-streaming-delta-lake)** — Real-time vehicle telemetry with Spark Structured Streaming: six cleaning rules, a quarantine table and city-partitioned Delta Lake tables on Databricks, plus a local PySpark version.
- **[RAG-TEND-TFG](https://github.com/Oppen-OC/RAG-TEND-TFG)** — Bachelor's thesis. Scrapes Spanish public tenders and extracts 47 structured fields with RAG + Llama 3.3 into SQL Server for analytics.
- **[finanzas](https://github.com/Oppen-OC/finanzas)** — Local-first personal finance ledger for Spanish bank exports: idempotent import, LLM-written categorisation rules, metrics and scenarios. FastAPI + SQLite + htmx.

## Stack

- **Languages:** Python, SQL, C, Bash
- **Data engineering:** Spark (Structured Streaming), dbt, DuckDB, PostgreSQL, Delta Lake, Debezium, Redis Streams, SQL Server
- **ML / AI:** XGBoost, LightGBM, Optuna, MLflow, DVC, LangChain, RAG
- **Platforms & tooling:** Docker, GitHub Actions, Databricks, FastAPI, Streamlit
