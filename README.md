# 4Tous Runtime  
A lightweight, open‑source local LLM runtime inspired by Ollama.

## 🚀 Overview
4Tous Runtime provides:

- A simple **HTTP API** for text generation  
- A **CLI tool** for running models locally  
- A modular **runner interface** (swap engines easily)  
- Support for **GGUF models** via llama.cpp or other backends  

This project demonstrates system architecture, API design, and AI runtime engineering.

---

## 🧱 Architecture

- **Server Layer** – Exposes `/api/generate`
- **Runner Layer** – Connects to model engines
- **CLI Layer** – Developer‑friendly interface
- **Config Layer** – Environment‑based configuration

See `docs/architecture.md` for diagrams.

---

## 📦 Installation

```bash
git clone https://github.com/<you>/4tous
cd 4tous
go build ./cmd/4tous

