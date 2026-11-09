<div align="center">

# Omar Al-Qattan
### Computer & Communication Engineer · AI Builder · Shawarma Enthusiast 🌯

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-al-qattan-1427291b4/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/_o_ronin_o_/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/o-ronin-o)

*"Learning by building from scratch, one algorithm at a time."*

</div>

---

## About Me

Computer and Communication Engineering student at Alexandria University (CGPA: 3.26/4.0) with a deep obsession for understanding things from the ground up, whether that's backpropagation, a Unix shell, or why shawarma hits differently after a long debug session.

I work across the full stack of CS: AI systems, agent frameworks, low-level systems programming, signal processing, DevOps, and everything in between. I believe the best way to truly understand something is to build it yourself.

---

## 💼 Experience

### AI Engineer Intern · Valeo · Egypt
*Jul 2026 – Sep 2026*

Built an AI-driven software integration platform that assists and automates repetitive tasks for automotive software integrators.

- 🤖 **Agent workflows:** designed LLM agents with MCP tools and task-specific skills that retrieve information, select tools, execute integration tasks, and report results
- 🔌 **MCP tooling:** built tools for working with automotive software repositories, AUTOSAR configurations, ARXML data, requirements, and engineering information sources
- 🔀 **Cross-repo workflows:** compare software versions, identify relevant code and configuration changes, and transfer them between source and target repositories
- 🧑‍✈️ **Human-in-the-loop safety:** change previews and mandatory engineer approval before any critical software modification is applied
- 📡 **Real-time telemetry:** live task status, progress, questions, and results flowing between the background AI process, a Node.js backend, and a React frontend
- 🕸️ **Architecture visualization:** parses ARXML databases into object-oriented graph nodes and edges (components, compositions, interfaces, ports, connections), then generates Mermaid diagrams for user-selected subsets using BFS traversal with configurable depth

**Stack:** Python · LLMs · MCP · AUTOSAR/ARXML · Node.js · React · Mermaid

---

## 🌟 Featured Projects

### 🎙️ Project SHATO — Speech-to-Action Orchestrator
> *Voice → LLM → Validated Action → Speech. End-to-end.*

A fully containerized, microservices-based voice pipeline where each stage (STT, LLM+RAG, Validator, TTS) lives as an independent FastAPI service orchestrated via Docker Compose. It includes a Gradio UI, a single REST endpoint (`POST /process_audio`) that returns everything in one shot, and a custom data pipeline to augment RAG training examples.

**Stack:** Python · FastAPI · Docker · LLMs · RAG · Speech Processing

---

### 🤖 Gemini Orchestrator
> *A production-ready wrapper around Gemini CLI.*

A layered, FSM-based architecture (UI → Controller → Planner → Execution Subagents) that turns a CLI agent into a controllable system. Backed by a full 25-test suite.

**Stack:** Python · FastAPI · Gradio · Pydantic · structlog · aiofiles
---

### 🧩 Multi-Agent Orchestrator for Codex CLI
> *Coordinating independent coding-agent sessions.*

A Python orchestrator that runs and coordinates independent Codex CLI sessions, with agent isolation, directory scoping, and structured output. Includes a packaged Codex skill that enforces strict JSON output contracts through an MCP `save_json` tool, so a UI can read agent results reliably from files.

**Stack:** Python · MCP · Codex CLI · Agent Frameworks
---

### 🫀 Heart Sound Diagnosis AI (PCG Ensemble Framework)
> *Detecting cardiac conditions through sound.*

A research-grade ensemble learning framework for phonocardiogram (PCG) classification using TS2Vec embeddings, with strict data-leakage prevention (`StratifiedGroupKFold`), calibration, bootstrap confidence intervals, and modular YAML-driven configuration.

**Stack:** Deep Learning · Signal Processing · TensorFlow · Scikit-learn
---

### 🧠 LLM Alignment Pipeline
> *Fine-tuning small LLMs end to end.*

An SFT pipeline for Qwen2-1.5B using Q-LoRA (`peft` + TRL), designed to mirror an existing RoBERTa full fine-tuning interface, with work on DPO, quantization, and Weights & Biases tracking.

**Stack:** PyTorch · Hugging Face · PEFT · TRL · W&B
---

## 🔧 Other Projects Worth Noting

| Domain | Project | What it is |
|--------|---------|------------|
| 🌐 Networking | HTTP/1.0 over Reliable UDP | Stop-and-Wait ARQ, MD5 checksums, 3-way handshake |
| 🧠 ML | [Neural Network from Scratch](https://github.com/o-ronin-o/Neural-Network-Scratch) | Full backprop + gradient descent, NumPy only |
| 🧠 ML | [Unsupervised Learning Pipeline](https://github.com/o-ronin-o/unsupervised-learning-from-scratch) | PCA, Autoencoders, K-Means, GMM — benchmarked |
| 🧠 ML | [Decision Trees & Random Forest](https://github.com/o-ronin-o/decision-trees-random-forest_from_scratch_probabilistic-classifier) | Ensemble methods built from scratch |
| 👁️ CV | [Adversarial CNN](https://github.com/o-ronin-o/phase2-task1.3-adversarial-cnn) | Robustness & adversarial examples in deep learning |
| 💻 Systems | [Mini Shell](https://github.com/o-ronin-o/mini-shell) | Unix shell with pipelines, signals & IPC |
| 💻 Systems | [Parallel Algorithms](https://github.com/o-ronin-o/mergesort-matrix-multiplication-THREADS) | Multithreaded merge sort & matrix multiplication |
| 🐳 DevOps | [Full-Stack Orchestration](https://github.com/o-ronin-o/orchstrating-frontend-backend-DB) | Frontend + backend + DB containerized with Docker |
| 📊 Data | [F1 EDA](https://github.com/o-ronin-o/f1-EDA-project) | Exploratory analysis on Formula 1 datasets |

---

## 🛠️ Tech Stack

**Languages:** Python · C · C++ · Java · JavaScript · MATLAB · Shell  
**AI/ML:** TensorFlow · PyTorch · NumPy · Scikit-learn · Hugging Face (PEFT/TRL) · LLMs · RAG · MCP · Agent Workflows · Fine-tuning (LoRA/DPO) · Computer Vision  
**Automotive:** AUTOSAR · ARXML  
**Networking:** TCP/IP · UDP · Digital & Wireless Communications · Signal Processing  
**Systems:** Threading · IPC · Process Management · Parallel Computing  
**DevOps:** Docker · Docker Compose · CI/CD · Microservices · FastAPI · Node.js · React  
**Data:** Pandas · Matplotlib · SQL · ETL Pipelines · Statistical Analysis
