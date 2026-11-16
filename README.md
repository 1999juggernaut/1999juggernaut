# Hi, I'm Sudhanshu 👋

**Agentic AI Engineer · LLM & Backend Systems**

I build AI systems that hold up in production: tool-calling agents, retrieval (RAG) over real documents, and the
async, retry-safe backends around them. 3.5+ years shipping enterprise software (Python, FastAPI, Salesforce/Apex),
now focused on agent reliability: queue-based orchestration, idempotent callbacks, schema-validated tool I/O,
evaluation gates and cost controls.

[LinkedIn](https://www.linkedin.com/in/sudhanshu-singh-1b3174179/)

---

### Featured projects

| Project | What it shows |
|---|---|
| [**visual-product-search**](https://github.com/sudhanshu-1999/visual-product-search) | Identify the exact product (SKU) from a customer photo: image embeddings (DINOv2 / SigLIP2) + vision-LLM re-ranking, served as a FastAPI API **and an MCP tool**, with multi-tenant auth, versioned catalogue, golden-set eval gate and a budget breaker. 34 tests, CI. |
| [**salesforce-llm-document-pipeline**](https://github.com/sudhanshu-1999/salesforce-llm-document-pipeline) | Async Salesforce → FastAPI → Docling → LLM → callback pipeline: Queueable callouts, retries with exponential backoff, idempotent jobs, failure isolation, job-status polling. Apex + pytest, CI. |
| [**yolov8-fall-detection**](https://github.com/sudhanshu-1999/yolov8-fall-detection) | Real-time fall detector (IIT Delhi capstone): **mAP@50 0.909**, 3.4 ms/image on a T4. Data-quality pipeline (corrupt/duplicate/outlier removal), training config and a video alerting script. |

### Tech I work with

| Area | Tools and techniques |
|---|---|
| **Agents & LLMs** | LangGraph (typed state, checkpointing, human-in-the-loop) · LangChain · CrewAI · Model Context Protocol (MCP) · tool/function calling · Pydantic tool schemas · ReAct / plan-and-execute |
| **RAG & search** | FAISS · ChromaDB · Vertex AI Vector Search · sentence-transformers · hybrid BM25 + dense · re-ranking · chunking |
| **Reliability & evals** | async job orchestration · retries with backoff · dead-letter queues · golden sets · LLM-as-a-judge · prompt-injection containment |
| **Backend & cloud** | Python · FastAPI · Docker · GCP (Cloud Run, Vertex AI, Gemini, Pub/Sub, Firestore, BigQuery) · Terraform |
| **ML & CV** | PyTorch · YOLOv8 · OpenCV · scikit-learn · transformers |
| **Salesforce** | Apex (triggers, batch, queueable) · LWC · Flows · Apex REST · Named Credentials · Data 360 (Data Cloud) |

### Certifications

**Salesforce**
- Salesforce Certified Data 360 Consultant (formerly Data Cloud Consultant), 2025
- Salesforce Certified Platform Developer, 2024
- Salesforce Certified Platform Foundations, 2023

**Anthropic**
- Claude Certified Architect – Foundations, 2026
- Introduction to Model Context Protocol · Introduction to Agent Skills · Claude Code in Action

**Education**
- Advanced AI & Deep Learning Programme, IIT Delhi
