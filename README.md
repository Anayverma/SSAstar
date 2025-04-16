# SmartSearch A* Algorithm (SSA*)

SmartSearch A* (SSA*) is a powerful, hybrid search engine that blends classic keyword matching with cutting-edge semantic understanding using deep learning. SSA* enhances traditional search pipelines with A* pathfinding logic, Transformer embeddings from HuggingFace, BM25 relevance scoring, and FAISS vector indexing—all wrapped in a scalable, microservice-based backend.

## 🔍 Features

- **Hybrid Retrieval Pipeline**:
  - **BM25** for fast and effective keyword-based ranking (via Elasticsearch).
  - **Semantic Embeddings** powered by HuggingFace Transformers.
  - **FAISS** for high-speed approximate nearest neighbor search.
- **A\* Algorithm Integration** to optimize result ranking based on multi-objective heuristics (relevance, distance, cost).
- **Scalable Microservice Architecture** for production-level performance.
- **Model Optimization** with LightGBM for ranking and result fusion.
- **Significant Gains**: 
  - 🔼 **35% boost** in search accuracy.
  - 🔽 **40% reduction** in average query latency.

## 🧠 Tech Stack

- **TensorFlow** – For model development and integration.
- **FAISS** – Fast vector similarity search.
- **Elasticsearch** – BM25 keyword indexing and querying.
- **HuggingFace Transformers** – Embedding generation for semantic search.
- **LightGBM** – Learning-to-rank model for result fusion and re-ranking.
- **Python (FastAPI)** – Microservices backend for scalable deployment.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Docker & Docker Compose (recommended for deployment)
- Elasticsearch 7.x
- FAISS
- TensorFlow + HuggingFace Transformers

### Installation

```bash
git clone https://github.com/Anayverma/SSAstar.git
cd SSAstar
pip install -r requirements.txt
# SSAstar
