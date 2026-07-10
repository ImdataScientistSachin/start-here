# Sachin Paunikar — Portfolio Index

**AI/ML Engineer building monitored, deployed ML systems and agentic LLM pipelines.**

👉 [LinkedIn](https://www.linkedin.com/in/sachin-paunikar/) · [GitHub](https://github.com/ImdataScientistSachin) · [Email](mailto:ImdeveloperSachin@gmail.com)

---

## Projects

### 1. 🛡️ Bias Drift Guardian
**Real-time fairness & drift monitoring for production ML models**

| | |
|---|---|
| **Stack** | Python, FastAPI, Streamlit, SHAP, Fairlearn, Docker, GitHub Actions |
| **Datasets** | German Credit, Adult Census, COMPAS Recidivism |
| **Unique feature** | Intersectional bias detection (sex × age × race) — not available in standard tools |
| **Compliance framing** | EEOC / EU AI Act |
| **Demo** | [Live Streamlit app](https://bias-drift-guardian.streamlit.app) |
| **Repo** | [Bias-Drift-Detector](https://github.com/ImdataScientistSachin/Bias-Drift-Detector) |

> *What I'd improve next:* Add PSI trend alerts on a sliding window; integrate with an MLflow model registry so drift events are linked to the model version that produced them.

---

### 2. 🤖 RetinaFace Pro
**Production face detection, landmark localisation, and identity verification**

| | |
|---|---|
| **Stack** | Python, TensorFlow, OpenCV, MLflow, Pytest, Docker, Streamlit |
| **Deployment** | Hugging Face Spaces |
| **Benchmarks** | ~45ms single-face latency, ~22 FPS on GTX 1650 |
| **Engineering highlights** | MLflow-tracked confidence drift, CI with Pytest |
| **Demo** | [Hugging Face Space](https://imdatascientistsachin-ratina-face.hf.space) |
| **Repo** | [RetinaFace-Detection](https://github.com/ImdataScientistSachin/RetinaFace-Detection) |

> *What I'd improve next:* Add a one-to-many identity store backed by a vector database so verification scales beyond in-memory embedding lookup.

---

### 3. 🎬 Transcript-to-Ad Generator
**Async generative pipeline: transcript → NLP extraction → ad copy → video preview**

| | |
|---|---|
| **Stack** | Python, spaCy, Ollama (local LLM), MoviePy, Redis Queue, FastAPI, Streamlit, Docker |
| **Architecture** | Async job queue separates UI from heavy rendering |
| **Repo** | [Transcript-to-Ad-Generator](https://github.com/ImdataScientistSachin/Transcript-to-Ad-Generator) |

> *What I'd improve next:* Replace local Ollama with a structured-output Groq call to reduce generation latency; add per-job status polling via WebSocket.

---

### 4. 🧠 llm-playbook
**RAG pipelines and tool-using agents with a retrieval evaluation harness**

| | |
|---|---|
| **Stack** | Python, LangChain, FAISS, Groq API, FastAPI |
| **What's measured** | Recall@3, Recall@5, MRR on a labeled Q&A set |
| **Repo** | [llm-playbook](https://github.com/ImdataScientistSachin/llm-playbook) |

> *What I'd improve next:* Add DBSF fusion as a retrieval variant to compare against FAISS flat; add answer faithfulness scoring (citation-grounded).

---

### 5. 🔊 Urban Sound Classifier
**96.63% accuracy audio classification with a hybrid U-Net + CNN architecture**

| | |
|---|---|
| **Stack** | Python, TensorFlow, mel-spectrograms, REST API |
| **Dataset** | UrbanSound8K (10 classes) |
| **Repo** | [Urban-Sound-Classifier-Project](https://github.com/ImdataScientistSachin/Urban-Sound-Classifier-Project) |

---

## Skills at a glance

| Area | Tools |
|---|---|
| Programming | Python, SQL |
| ML/DS | Scikit-learn, TensorFlow, Fairlearn, SHAP |
| Agentic AI / LLM | LangChain, RAG (FAISS), Groq API |
| MLOps / Infra | Docker, MLflow, GitHub Actions CI, Pytest, Redis Queue |
| Deployment | FastAPI, Streamlit, Hugging Face Spaces |
