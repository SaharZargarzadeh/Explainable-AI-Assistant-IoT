# 🤖 Explainable AI Assistant for IoT Power Anomaly Detection  
*Built with Gemini 1.5 Pro + RAG – Google GenAI Capstone 2025*

![Python](https://img.shields.io/badge/python-3.10+-blue)
![Gemini](https://img.shields.io/badge/Gemini-1.5_Pro-green)
![RAG](https://img.shields.io/badge/GenAI-RAG_Enabled-purple)
![Status](https://img.shields.io/badge/status-Completed-success)

---

## 📘 Overview

This project is part of the **Google 5-Day Generative AI Capstone (2025)** and showcases a research-aligned solution: an explainable AI chatbot that interprets **power anomalies in IoT devices**.

💡 The assistant is powered by **Gemini 1.5 Pro** and utilizes **Retrieval-Augmented Generation (RAG)** to provide grounded, explainable feedback to engineers and non-technical users.

> 📍 Domain relevance: Smart homes, industrial IoT, embedded systems  
> 📍 Research relevance: Power-aware adversarial ML, signal-based anomaly detection

---

## 💬 Motivation

In my PhD research, I explore how adversarial behavior affects power consumption in IoT systems. While traditional anomaly detectors can flag strange behavior, **they rarely explain the "why."**

This project aims to bridge that gap — providing a **trustworthy, explainable AI** assistant for cybersecurity use cases.

---

## 🧠 GenAI Capabilities Demonstrated

| Capability               | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Few-Shot Prompting**   | Classify & explain signals with example-driven prompts                      |
| **Embeddings + Search**  | Convert signals to vectors and find semantic matches                        |
| **Grounding with RAG**   | Use domain-specific docs to improve accuracy & trustworthiness of responses |

---

## 🔍 What It Does

- 🧠 Classifies anomalies in power traces (e.g. drops, spikes, noise)
- 💬 Explains the potential causes in natural language
- 📎 Grounds responses using relevant domain docs
- 🛠️ Supports technician-facing and non-expert-friendly outputs

---

## 📂 Repo Structure

├── rag_pipeline.ipynb       # Main notebook

├── power_data/              # Sample IoT power signals

├── sample_prompts/          # Few-shot examples for classification

├── utils/                   # Helper functions

├── README.md

├── requirements.txt



---

## 🚀 How to Run

### 1. Clone the Repo

```bash
git clone https://github.com/SaharZargarzadeh/Explainable-AI-Assistant-IoT.git
cd Explainable-AI-Assistant-IoT
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```


### 3. Launch the Notebook
    Use Jupyter Lab, Jupyter Notebook, or VSCode:

```bash
jupyter notebook rag_pipeline.ipynb
```

