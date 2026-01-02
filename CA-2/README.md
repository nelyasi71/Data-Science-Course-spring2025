
# CA-2: Data Engineering & Streaming

This assignment focuses on **building and running a simple data streaming pipeline** using Kafka and Docker,
followed by **data consumption, storage, and analysis** using Python.

The goal is to gain hands-on experience with **streaming systems, containerized environments, and data pipelines**.

---

## What This Project Does

In this project, I implemented a data pipeline that:

- Produces and consumes streaming data using **Kafka**
- Runs inside a **Dockerized development environment**
- Stores streamed data for further processing
- Analyzes and visualizes the collected data using Python

This assignment emphasizes **infrastructure setup and data flow**, rather than complex modeling.

---

## 📂 Project Files and Purpose

| File                        | Purpose                                     |
| --------------------------- | ------------------------------------------- |
| `DS-CA2.pdf`              | Assignment description and instructions     |
| `docker-compose-dev.yaml` | Development Docker setup with hot-reloading |
| `Dockerfile`              | Python service container definition         |
| `kafka_consumer.py`       | Kafka consumer implementation               |
| `darooghe_pulse.py`       | Streaming data producer                     |
| `notebook.ipynb`          | Data analysis and visualization             |
| `requirements.txt`        | Python dependencies                         |

---

## Implemented Components

### 🔹 Streaming Layer

- Kafka topics used for data streaming
- Python-based producer and consumer
- Real-time message consumption

### 🔹 Data Storage

- Streamed data stored for later analysis
- Integration with MongoDB (via Docker)

### 🔹 Analysis

- Loaded streamed data into Pandas
- Performed exploratory analysis
- Generated plots and summaries in Jupyter

---

## Environment Setup

Use the **development Docker Compose file** for hot-reloading:

```bash
docker-compose -f docker-compose-dev.yaml up --build
```
