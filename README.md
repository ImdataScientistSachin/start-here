<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff88,100:6e40c9&height=220&section=header&text=Sachin%20Paunikar&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Agentic%20AI%20Engineer%20%7C%20LLM%20Infrastructure%20%7C%20MLOps&descAlignY=58&descSize=19&animation=fadeIn" width="100%"/>

# 🚀 Engineering Portfolio Hub — Start Here

**Architecting Autonomous Agentic AI Pipelines, LLM Infrastructure & Production MLOps Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sachin-paunikar)
[![GitHub Profile](https://img.shields.io/badge/GitHub-ImdataScientistSachin-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ImdataScientistSachin)
[![Email](https://img.shields.io/badge/Email-ImdataScientistSachin%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ImdataScientistSachin@gmail.com)
[![CodeSlim Anchor](https://img.shields.io/badge/🤖_Anchor-CodeSlim-6e40c9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ImdataScientistSachin/CodeSlim)

</div>

<div align="center">

**Quick Navigation:**  
[🤖 1. CodeSlim](#1--codeslim--agentic-ai-code-quality-engine-anchor) • [🔬 2. LensIntel](#2--lensintel--production-deepfake-forensics-engine) • [🛡️ 3. Bias Drift Guardian](#3--bias-drift-guardian--real-time-fairness--drift-monitor) • [⚡ 4. More Systems](#4--production-ml--nlp-pipelines) • [🧰 Tech Stack](#-technology--infrastructure-matrix) • [🤝 Open To](#-open-to--contact)

</div>

---

## 💡 Executive Engineering Summary

> **"Most AI applications fail in production not because of model capability, but because of context bloat, unhandled latency, structural fragility, and unmonitored drift."**

I build the **deterministic guardrails, token optimizers, multi-agent DAGs, and monitoring infrastructure** that make generative AI and machine learning systems reliable, cost-efficient, and production-safe.

---

## 🏆 Featured Systems & Architecture Index

### 1. 🤖 CodeSlim — Agentic AI Code Quality Engine (Anchor)
**The deterministic guardrail sitting between LLMs and production codebases — cutting token bloat by 76%.**

| Dimension | Details |
|---|---|
| **Core Problem** | LLMs produce bloated, duplicate, and structurally fragile code that wastes tokens and introduces hidden bugs. |
| **Architectural Solution** | 6-stage stateful LangGraph DAG enforcing static analysis (Radon/Vulture/Lizard) + LibCST AST losslessness before LLM refactor. |
| **Impact Metrics** | **76% token reduction**, **96/96 pytest cases passing**, **$0 cost for 80% of fixes** (via C-native CST node). |
| **Tech Stack** | `Python 3.11` `LangGraph` `LibCST` `Radon` `Vulture` `FastAPI` `Ollama` `Docker` `Railway` |
| **Key Links** | [⭐ GitHub Repository](https://github.com/ImdataScientistSachin/CodeSlim) • [📄 Technical Architecture Guide](https://github.com/ImdataScientistSachin/CodeSlim/blob/main/documents/CODESLIM_GUIDE.md) |

```text
[Raw AI Code] → [Stage 1: Radon & Vulture Sensors] → [Stage 2: LibCST Lossless Prune] 
               → [Stage 3: $0 CST Fix Node] → [Stage 4: LangGraph LLM Refactor (Ollama/Groq/OpenAI)] 
               → [Stage 5: AST Safety Gate (ast.parse)] → [Stage 6: HTML Observatory Diff]
```

> **Design Trade-off & Next Steps:** *Local-first Ollama inference (`qwen2.5-coder:3b`) reduces cloud API cost to zero but incurs GPU latency on low-end hardware. Next optimization: Implement vLLM continuous batching and speculative decoding for 4x throughput.*

---

### 2. 🔬 LensIntel — Production Deepfake Forensics Engine
**Multi-model AI forensics platform producing ISO 27037-compliant, court-admissible forensic reports.**

| Dimension | Details |
|---|---|
| **Core Problem** | Single-model deepfake detectors fail on unseen compression algorithms and adversarial face swaps. |
| **Architectural Solution** | Ensembled forensic pipeline merging 5 independent detection models with a LLaMA 3.3 AI Co-Pilot verdict generator. |
| **Detection Models** | Frequency domain analysis, DCT coefficient mapping, noise variance, face landmark geometry, CLIP zero-shot embedding. |
| **Compliance & Output** | ISO 27037 forensic chain-of-custody logging + instant PDF/JSON audit reports for legal admissibility. |
| **Tech Stack** | `React 18` `FastAPI` `Temporal.io` `CLIP` `FAISS` `LLaMA 3.3` `Docker` |
| **Key Links** | [⭐ GitHub Repository](https://github.com/ImdataScientistSachin) |

> **Design Trade-off & Next Steps:** *Temporal.io orchestrates multi-step video frame extraction reliably, but high-resolution processing creates storage bottlenecks. Next optimization: Stream frame chunks directly to web workers with WebAssembly-accelerated DCT transforms.*

---

### 3. 🛡️ Bias Drift Guardian — Real-Time Fairness & Drift Monitor
**Intersectional bias detection & automated data drift monitoring aligned with EEOC & EU AI Act standards.**

| Dimension | Details |
|---|---|
| **Core Problem** | Standard AI audit tools test one attribute at a time (e.g. gender OR age), missing compound subgroup discrimination. |
| **Architectural Solution** | Intersectional subgroup analyzer (Gender × Age × Subgroup) coupled with Population Stability Index (PSI) & Kolmogorov-Smirnov drift triggers. |
| **Regulatory Alignment** | EEOC 4/5th Rule compliance checks, SHAP feature importance drift attribution, DiCE counterfactual XAI. |
| **Tech Stack** | `Python` `Streamlit` `FastAPI` `SHAP` `Fairlearn` `Docker` `GitHub Actions` |
| **Key Links** | [🔴 Live Interactive App](https://imdatascientistsachin-bias-drift-detector-dashboardapp-i2wbt8.streamlit.app/) • [⭐ GitHub Repository](https://github.com/ImdataScientistSachin/Bias-Drift-Detector) |

> **Design Trade-off & Next Steps:** *Streamlit enables rapid interactive monitoring dashboards, but scaling to streaming event buses requires decoupling UI from inference. Next optimization: Export telemetry via OpenTelemetry directly to Grafana dashboards.*

---

### 4. ⚡ Production ML & NLP Pipelines

#### 🎬 Transcript-to-Ad Generator
* **What it does:** Async NLP video generation pipeline transforming raw video/audio transcripts into structured NER entities, LLM ad scripts, and rendered video clips.
* **Stack:** `spaCy` `Ollama (Local LLM)` `MoviePy` `Redis Queue` `FastAPI` `Docker`
* **Architecture:** Redis task queue decouples heavy MoviePy video rendering from FastAPI client endpoints.
* **Repo:** [Transcript-to-Ad-Generator](https://github.com/ImdataScientistSachin/transcript_To_Ad_Generation-)
* **Next Improvement:** Migrate local LLM script generation to Groq API for sub-second structured output & add WebSocket progress streaming.

#### 🧠 LLM-PlayBook & Retrieval Evaluation Harness
* **What it does:** End-to-end RAG architecture benchmarking vector retrieval performance across chunking strategies and embedding models.
* **Metrics Tracked:** Recall@3, Recall@5, Mean Reciprocal Rank (MRR) on human-annotated test datasets.
* **Stack:** `LangChain` `FAISS` `Groq API` `FastAPI` `Docker`
* **Repo:** [llm-playbook](https://github.com/ImdataScientistSachin/llm-playbook)
* **Next Improvement:** Integrate Hybrid Search (BM25 keyword + FAISS dense vectors) with Reciprocal Rank Fusion (RRF).

#### 🔊 Urban Sound Classifier
* **What it does:** Environmental audio classification achieving **96.63% accuracy** on UrbanSound8K using hybrid U-Net + CNN spectrogram models.
* **Stack:** `TensorFlow` `U-Net` `Librosa` `TFLite` `Flask`
* **Repo:** [Urban-Sound_Classifier-Project](https://github.com/ImdataScientistSachin/Urban-Sound_Classifier-Project)

#### 👤 RetinaFace Pro Face Verification Pipeline
* **What it does:** Computer vision pipeline performing ~45ms real-time face detection, landmark alignment, and identity verification.
* **Stack:** `TensorFlow` `OpenCV` `RetinaFace` `ArcFace` `MLflow` `HuggingFace Spaces`
* **Live Demo:** [HuggingFace Space Demo](https://imdatascientistsachin-ratina-face.hf.space)

---

## 🧰 Technology & Infrastructure Matrix

| Layer | Technologies & Frameworks |
|---|---|
| **Agentic AI & LLM Engineering** | LangGraph (Stateful DAGs), LangChain, Ollama (Local LLM), Groq, OpenAI API, LLaMA 3.3, Tool Calling |
| **AST & Deterministic Tooling** | LibCST, Tree-Sitter, Radon (Cyclomatic Complexity), Vulture (Dead Code), tiktoken |
| **MLOps & Pipeline Deployment** | Docker, Docker Compose, FastAPI, Railway, GitHub Actions (CI/CD), Temporal.io, Redis Queue |
| **Machine Learning & Deep Learning** | PyTorch, TensorFlow, Scikit-learn, XGBoost, U-Net, OpenCV, spaCy, Librosa |
| **Monitoring, XAI & Compliance** | SHAP, Fairlearn, DiCE Counterfactuals, PSI / KS Drift Detection, EEOC / EU AI Act Frameworks |
| **Data & Vector Stores** | PostgreSQL, SQL, FAISS, CLIP Zero-Shot, Pandas, NumPy, Redis |

---

## 📐 Engineering Principles & QA Standards

1. **Deterministic-First Execution:** Never call an expensive LLM for tasks solvable by C-native static analysis or AST transformation ($0 cost baseline).
2. **Strict AST Guardrails:** Every code transformation must pass `ast.parse()` syntax validation before committing changes—zero hallucinated code syntax allowed.
3. **Rigorous Test Enforcement:** All flagship projects maintain automated test suites (e.g., CodeSlim's 96/96 passing pytest suite).
4. **Transparent Trade-offs:** Every system documents design choices, latency overheads, and next architectural improvements.

---

## 🤝 Open To & Contact

🎯 **Target Roles:** Agentic AI Engineer • LLM Infrastructure Specialist • MLOps Engineer • AI/ML Engineer  
🌍 **Location & Availability:** Remote (Global) • India Tech Hubs (Pune, Bangalore, Hyderabad, Mumbai)  
📬 **Direct Contact:** [ImdataScientistSachin@gmail.com](mailto:ImdataScientistSachin@gmail.com) • [LinkedIn Profile](https://www.linkedin.com/in/sachin-paunikar/)

```text
"Build AI infrastructure that is fast, safe, auditable, and production-ready."
```
