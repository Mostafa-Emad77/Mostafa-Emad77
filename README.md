# Hi, I'm Mostafa Emad

### AI Engineer | LLM & Voice AI Systems | Arabic NLP | RAG & Agentic Workflows

I'm an **AI Engineer based in Egypt** focused on building production-ready AI systems across **LLMs, Voice AI, NLP, RAG, and agentic workflows**.

My work sits between **model development and production engineering** — from fine-tuning speech and transformer models to designing multi-agent systems, deploying LLM inference, and building low-latency AI applications.

I have a particular interest in **Arabic and multilingual AI**, especially speech, language understanding, and real-world AI systems that need to operate reliably outside the notebook.

---

## What I Work On

- **LLM Systems** — inference, serving, tool calling, structured generation, and production integration
- **Voice AI & ASR** — multilingual speech recognition, keyword spotting, voice agents, and real-time pipelines
- **Arabic NLP** — Arabic language models, speech systems, punctuation restoration, and multilingual NLP
- **Agentic AI** — LangGraph workflows, multi-stage reasoning pipelines, tool orchestration, and validation
- **RAG Systems** — semantic retrieval, hybrid search, vector databases, and knowledge graphs
- **AI Infrastructure** — FastAPI, Docker, gRPC, vLLM, ONNX/TFLite, and low-latency inference

---

## Featured Projects

### AuditMind — Bilingual Agentic Financial Auditor

A production-oriented **Arabic/English financial document auditing system** combining hybrid retrieval, knowledge graphs, and agentic workflows.

**Highlights**
- Hybrid **Qdrant vector search + Neo4j knowledge graph**
- Multi-stage **LangGraph audit pipeline**
- Cross-document contradiction detection and validation
- Confidence-gated findings and bounded replanning
- Concurrent document processing and LLM adjudication
- Extensive automated backend testing

**Tech:** `Python` `FastAPI` `LangGraph` `Qdrant` `Neo4j` `Redis` `Next.js`

---

### Naqta — Arabic Punctuation Restoration

Arabic punctuation restoration model based on **XLM-RoBERTa-large**.

- **97.14% token accuracy**
- **Macro F1 ≈ 0.896**
- Evaluated on a held-out dataset containing **5M+ tokens**
- Trained across multiple experimental runs with focal loss and rare-class handling
- Published as a research paper on **SSRN (2026)**

**Tech:** `PyTorch` `Hugging Face` `XLM-RoBERTa` `Arabic NLP`

---

### Fahim (فهيم) — Arabic Speech-to-SQL Voice Assistant

A fully local Arabic voice assistant that converts spoken natural-language questions into secure SQL queries.

**Pipeline**

`Arabic Speech → ASR → LLM → SQL Validation → Database → Arabic Response → TTS`

**Highlights**
- Fully local inference with **zero cloud dependency**
- faster-whisper ASR with INT8 inference
- Local LLM serving through Ollama
- SQL validation using regex + AST parsing
- Prompt-injection protection
- Automatic schema generation from uploaded CSV/Excel datasets

**Tech:** `FastAPI` `faster-whisper` `Ollama` `SQLGlot` `MySQL` `TTS`

---

### Multilingual Offline Voice Command Recognition

Built lightweight speech-command models for **English, French, Mooré, Dioula, and Fulfulde** for an offline voice-first learning application.

- Designed for **on-device Android inference**
- Optimized compact speech models
- INT8 model deployment using **TFLite**
- Built for low-resource multilingual speech scenarios

**Tech:** `TensorFlow` `DS-CNN` `TFLite` `Speech Processing`

---

## Production AI Experience

Beyond personal projects, I've worked on production systems involving:

- Arabic-English **code-switched ASR**
- Real-time voice-agent pipelines
- Barge-in and interruption detection
- Spoken-language identification
- Egyptian Arabic keyword detection
- **30B-parameter LLM serving with vLLM on AWS H100 GPUs**
- Agentic AI and tool-calling systems
- Large-scale RAG and data-processing pipelines
- Edge and on-device model deployment

---

## Tech Stack

**Languages**

`Python` `SQL` `JavaScript` `C/C++`

**AI / NLP / Speech**

`PyTorch` `TensorFlow` `Hugging Face Transformers` `wav2vec2` `XLM-RoBERTa` `faster-whisper` `spaCy`

**LLM & Agentic AI**

`LangChain` `LangGraph` `LlamaIndex` `Ollama` `vLLM`

**Retrieval & Data**

`Qdrant` `Neo4j` `FAISS` `Redis` `Supabase` `DuckDB`

**Backend & Infrastructure**

`FastAPI` `Flask` `gRPC` `Docker` `AWS` `ONNX` `TFLite`

---

## Areas of Interest

```text
LLM Systems
Voice AI
Arabic & Multilingual NLP
Agentic AI
Retrieval-Augmented Generation
Speech Recognition
Low-Latency Inference
Model Fine-Tuning
AI Infrastructure
Edge AI
```

---

## Connect With Me

- [LinkedIn](https://www.linkedin.com/in/mostafa-emad-al-din-5361831b9/)
- [Hugging Face](https://huggingface.co/MostafaMaroof)
- Mostafa.maroof@hotmail.com

---

> I enjoy building AI systems that go beyond demos — models and applications designed around real deployment constraints, measurable performance, and reliable production behavior.
